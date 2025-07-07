pipeline {
    agent {
        docker { image 'node:18' }
    }
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/saeedkhan-github/Git-Webhook-Practice.git'
            }
        }
        stage('Execute') {
            steps {
                sh 'node echo.js'
            }
        }
    }
}