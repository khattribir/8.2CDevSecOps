pipeline {
    agent any

    environment {
        PATH = "/Users/birkhattri/.nvm/versions/node/v24.20.0/bin:${env.PATH}"
    }

    stages {

        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }

        stage('Run Tests') {
            steps {
                sh '
