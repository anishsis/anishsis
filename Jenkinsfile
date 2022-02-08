pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'echo STAGE1'
            }
        }
        stage('Test') {
            steps {
                sh 'python hello-world.py'
            }
        }
    }
}