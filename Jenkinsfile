pipeline {
    agent any

    stages {

        stage('Build from github') {
            steps {
               
            sh 'docker build -t jenkins .'
            }
        }
        stage('Deploy') {
            steps {
                echo 'deploying....'
                
            }
        }
        stage('Test') {
            steps {
                sh 'python -m unittest'
            }
        }
        
    }
}