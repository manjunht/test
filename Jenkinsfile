pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sudo apt-get update
                sudo apt-get install docker.io
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
