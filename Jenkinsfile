pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                bat 'echo Hello world' 
            }
        }
	stage('Test') { 
            steps {
                bat 'set' 
            }
        }
	post {
       	    always {
                junit 'target/surefire-reports/*.xml'
            }
        }
    }
}