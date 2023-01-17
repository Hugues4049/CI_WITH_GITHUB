pipeline {
    agent any

    stages {

        stage('Build from github') {
            steps {
               
            sh 'docker build -t jenkins .'
            }
        }
        stage('Test') {
            steps {
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