pipeline {
    agent {
        docker { image 'node:18-alpine' }
    }
    stages {
        stage('Build') {
            steps {
                sh 'node --version'
                sh 'npm install'
            }
        }
    }
}