pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/rafid-malik1/web-test.git'
            }
        }

        stage('Build') {
            steps {
                echo 'No build needed for static files.'
            }
        }

        stage('Test') {
            steps {
                echo 'No tests configured.'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment stage (optional).'
            }
        }
    }
}

