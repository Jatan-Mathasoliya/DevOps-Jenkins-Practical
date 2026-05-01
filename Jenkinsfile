pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Fetching code from GitHub'
            }
        }

        stage('Compile') {
            steps {
                bat 'javac Main.java'
            }
        }

        stage('Run') {
            steps {
                bat 'java Main'
            }
        }
    }
}