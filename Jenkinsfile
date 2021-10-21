pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'sudo apt-get update'
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
