pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the Python application...'
                sh 'pip install -r requirements.txt'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'pytest'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to test environment...'
                // Implement deployment steps
            }
        }
    }
}
