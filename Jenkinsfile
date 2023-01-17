pipeline {
    agent any

    stages {

        stage('Build from github') {
            steps {
               
            bat 'docker build -t jenkins .'
            }
        }
        stage('Test') {
            steps {
                echo 'deploying....'
        
            }
        }
        stage('Deploy') {
            steps {
                echo 'deploying....'
                
            }
        }
    }
}