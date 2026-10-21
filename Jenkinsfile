pipeline {
    agent any

    stages {
        stage('checkout code') {
            steps {
                echo 'Checking out source code...'
                // Declarative pipeline handles SCM checkout automatically
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
}
 post{
    success{
        bat'echo"build successfull"'
    }
    failure[
        bat'echo"failed"'
        }
}

