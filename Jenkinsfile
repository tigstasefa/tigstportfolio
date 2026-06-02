pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Example checkout step
                checkout scm
            }
        }
        stage('Build') {
            steps {
                echo 'ls -l index.html'
            }
        }
        stage('Test') {
            steps {
                echo 'Test code'
            }
        }
        stage('Deploy') {
            steps {
                echo 'deploy'
            }
        }
    }
}
