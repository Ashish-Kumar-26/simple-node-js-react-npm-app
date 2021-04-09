pipeline {
    agent {
        docker {
            image 'node:6-alpine' 
            args '-p 2000:2000' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                bat 'npm install' 
            }
        }
    }
}