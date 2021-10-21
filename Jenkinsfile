pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'apt-get update'
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
