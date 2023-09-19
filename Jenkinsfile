pipeline {
    agent { 
        docker {
            image 'python:3.11.5-alpine3.18'
            args '-v $HOME:/home/jenkins'
        } 
    }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
