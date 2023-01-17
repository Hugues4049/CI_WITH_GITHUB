'''pipeline{
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}'''



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