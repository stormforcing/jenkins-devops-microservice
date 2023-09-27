pipeline{
	
	agent{ docker{ image 'maven:3.6.6' } } 

	stages{
		stage('Build'){
			steps{
				sh 'mvn --version’
				echo 'Build'
			}
		}
		stage('Test'){
			steps{
				echo 'Test'
			}
		}
	}
} 
