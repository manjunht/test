pipeline {
    agent any
        

    stages {
        stage('Build') {
            steps {
                docker { image 'node:14-alpine' }
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
