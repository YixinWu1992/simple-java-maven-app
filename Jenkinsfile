pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                bat 'echo Hello world I am Gongyan Chen' 
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
                bat 'dir' 
		bat 'echo work complete, yeah!'
            }
        }
    }
}
