pipeline {
    agent any

    stages {

        stage('Build Docker Image') {
            steps {
                sh 'docker version'
                sh 'docker build -t tenimrout/test-app .'
            }
        }

    }
}
