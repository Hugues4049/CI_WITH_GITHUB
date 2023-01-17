pipeline {
    agent any

    stages {
        stage('Build from github') {
            steps {
                sh 'docker build .'
            }
        }
        stage('Test') {
            steps {
                echo 'deploying....'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}