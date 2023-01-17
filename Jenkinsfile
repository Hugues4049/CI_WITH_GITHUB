pipeline {
    agent any

    stages {
        stage('Build from github') {
            steps {
                '''sh 'docker build .'''
                sh 'docker build -t jenkins .'
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