pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'apt list'
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
