pipeline {
    agent any
    stages {
        stage('Build Docker Image') {
            steps {
                script {
                    def myImage = docker.build('my-simple-app')
                }
            }
        }
    }
}