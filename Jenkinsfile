pipeline {
    agent {
        docker {
            # image 'node:6-alpine' 
            image 'nodejs:6.11.5' 
            args '-p 3000:3000' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}
