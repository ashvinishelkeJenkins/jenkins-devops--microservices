//scripted

//Declarative

pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "build"
            }
        }
        stage('Test') { 
            steps {
                echo "test" 
            }
        }
        stage('Deploy') { 
            steps {
                echo "Deploy" 
            }
        }
    }
	post{
		always{
			echo "I am awesome. I run always"
		}
		success{
			echo "I run when you are successfull"
		}
		failure{
			echo "I run when you fail"
		}
	}
}
		

