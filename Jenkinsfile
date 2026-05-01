pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Code fetched from GitHub'
            }
        }

        stage('Build') {
            steps {
                bat 'echo Building project'
            }
        }

        stage('Test') {
            steps {
                bat 'echo Testing project'
            }
        }

        stage('Deploy') {
            steps {
                bat 'echo Deploying project'
            }
        }
    }
}