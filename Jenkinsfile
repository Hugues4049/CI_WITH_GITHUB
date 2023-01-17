pipeline {
    environment {
        registry = "hugues4049/https://github.com/Hugues4049/CI_WITH_GITHUB"
        registryCredential = 'dockerhub_id'
        dockerImage = ''
    }

    agent any

    stages {
        stage('Build our image') {
            steps {
                dockerImage = docker.build registry + ":$BUILD_NUMBER"
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