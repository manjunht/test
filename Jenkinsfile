pipeline {
    agent {
        docker { image 'node:14-alpine' }

    stages {
        stage('Build') {
            steps {
                echo 'stepd...'
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
