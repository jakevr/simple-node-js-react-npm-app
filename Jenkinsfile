pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh './jenkins/scripts/test.sh'
            }
        }
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}