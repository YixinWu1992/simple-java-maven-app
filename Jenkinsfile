pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                bat 'echo Hello world!!!!' 
            }
        }
	stage('Test') { 
            steps {
                bat 'set' 
            }
	    post {
       	        always {
                    bat 'echo Set complete'
                }
            }
        }
	stage('Deliver') { 
            steps {
                bat '.\jenkins\scripts\deliver.sh' 
            }
        }
    }
}