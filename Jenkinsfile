pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/umarmir/web-test.git'
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
