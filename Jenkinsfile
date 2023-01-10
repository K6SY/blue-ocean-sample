pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                sh 'docker build -t simple-flask-app:1.0.${env.BUILD_NUMBER} .'
            }
        }
    }
}