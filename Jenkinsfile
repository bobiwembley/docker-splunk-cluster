pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                docker-compose up -d
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
