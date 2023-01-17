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
                echo 'deploying....'
                sh 'run python3 -m unittest'
            }
        }
        stage('Deploy') {
            steps {
                echo 'deploying....'
                
            }
        }
    }
}