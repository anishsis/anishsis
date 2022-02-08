pipeline {
    agent { docker { image 'python:3.10.1-alpine' } }

    stages {
        stage('Build') {
            steps {
                sh 'echo STAGE1'
            }
        }
        stage('Test') {
            steps {
                sh 'python python hello-world.py'
            }
        }
    }
}