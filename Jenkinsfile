pipeline {
    agent any

    stages {
        stage('checkout code') {
            steps {
                echo 'Checking out source code...'
            }
        }
        stage('build') {
            steps {
                echo 'Building application...'
            }
        }
        stage('test') {
            steps {
                echo 'Running unit tests...'
            }
        }
        stage('deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }

    post {
        success {
            sh 'echo "build successful"'
        }
        failure {
            sh 'echo "failed"'
        }
    }
}
