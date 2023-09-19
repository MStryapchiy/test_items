pipeline {
    agent { 
        docker {
            args '-v $HOME:/var/lib/jenkins'
            image 'python:3.11.5-alpine3.18'
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
