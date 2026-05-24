pipeline {
    agent any

    stages {

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t hostel-app .'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "Deploy step placeholder"'
            }
        }
    }
}