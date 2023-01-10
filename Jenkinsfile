pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                sh 'docker build -t kalidousy/simple-flask-app:1.0.${env.BUILD_NUMBER} .'
            }
        }
    }
}