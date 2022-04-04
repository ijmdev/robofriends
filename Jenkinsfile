pipeline {
    agent {
        any
    }
    stages {
        stage('Echo') { 
            steps {
                sh 'echo hallo' 
            }
        }
        stage('Build') { 
            steps {
                sh 'npm test' 
            }
        }        
    }
}