pipeline {
    agent any
    stages {
        stage('Install dependencies') {
            steps {
                bat 'npm install'
            }
        }
        stage('Install dependencies') {
            steps {
                bat 'npm start'
            }
        }
        stage('Run security tests') { 
            steps {
                bat 'npm audit' 
            }
        }
        stage('Test') { 
            steps {
                bat 'npm run test' 
            }
        }
    }
}