pipeline {
    agent any

    stages {
        stage('Build from github') {
            steps {
                echo 'build...'
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