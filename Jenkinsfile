//scripted

//declarative
pipeline {
		agent any
		stages {
			stage('Build') {
				steps {
					echo "Build"
				}
			}
			stage('Test') {
				steps {
					echo "Test"
				}
			}	
			stage('Intergration Test') {
				steps {
					echo "Intergration Test"
				}
			}

		} post {
			always {
				echo "I am God, I always RUN!"
			}
			success{
				echo "I run when you are successful"
			}
			failure {
				echo "I run when you fail!"
			}
		}		
}
