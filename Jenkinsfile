pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/saeedkhan-github/Git-Webhook-Practice.git'
            }
        }
        stage('Install') {
            steps {
                script {
                    sh 'curl -sL https://deb.nodesource.com/setup_18.x | bash -'
                    sh 'apt-get install -y nodejs'
                }
            }
        }
        stage('Execute') {
            steps {
                sh 'node echo.js'
            }
        }
    }
}