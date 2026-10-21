pipeline {
    agent any
    stages {
        stage('checkout code') {
            steps {
                git 'https://github.com/Alihassan6442700/my_first_pipeline'
            }
        }
        stage('build') {
            steps {
                sh 'echo "building the application"'
            }
        }
        stage('test') {
            steps {
                sh 'echo "running tests"'
            }
        }
        stage('deploy') {
            steps {
                sh 'echo "deploying"'
            }
        }
    }
}
