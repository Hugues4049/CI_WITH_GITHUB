pipeline {
    agent any

    stages {

        stage('Build from github') {
            steps {
                echo 'build...'
                sh 'docker build -t jenkins .'
            }
        }
        stage('Test') {
            steps {
                echo 'deploying....'
                sh 'python3 -m unittest'
            }
        }
        stage('Deploy') {
            steps {
                echo 'deploying....'
                
            }
        }
    }
}