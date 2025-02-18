pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                // Pulls the latest code from your Git repository.
                checkout scm
            }
        }
        stage('Build') {
            steps {
                // Since this is a static site, “build” is just a placeholder.
                sh 'echo "Building the static site..."'
            }
        }
        stage('Test') {
            steps {
                // Insert testing or linting commands if needed.
                sh 'echo "Running tests (if any)..."'
            }
        }
        stage('Deploy') {
            steps {
                // For a static site, deployment might be copying files or uploading to a server.
                sh 'echo "Deploying the static site..."'
            }
        }
    }
}
