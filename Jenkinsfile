pipeline {
    agent {
        docker { image 'node:14-alpine' }

    stages {
        stage('Build') {
            steps {
                apt-get 'update'
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
