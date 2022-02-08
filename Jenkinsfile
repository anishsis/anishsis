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
                sh '/usr/bin/python python python hello-world.py'
            }
        }
    }
}