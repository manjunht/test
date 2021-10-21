pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                apt-get update
                apt-get install docker.io
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
