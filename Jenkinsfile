pipeline {
    agent any

    stages {
        stage('Build from github') {
            steps {
                sh docker.build("jenkins")
            }
        }
        stage('Test') {
            steps {
                echo 'deploying....'
            }
        }
        stage('Deploy') {
            steps {
                sh 'python3 -m unittest'
            }
        }
    }
}