pipeline {
    agent any 
    stages {
        stage('Npm install') { 
            steps {
                bat 'npm install'
            }
        }
        stage('Test') { 
            steps {
               bat 'npm run test'
            }
        }
    }
}
