pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Cloning repository...'
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
                // sh 'your-build-command-here'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // sh 'your-test-command-here'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                // sh 'your-deploy-command-here'
            }
        }
    }
}
