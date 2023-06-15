pipeline {
    agent { label 'slave1' }
    stages {
        stage('chechkout') {
            steps {
                sh 'echo chechkout jenkins file'
            }
        }
         stage('testing') {
            steps {
                sh 'echo testing code'
            }
        }
         stage('deploying') {
            steps {
                sh 'echo code to deploy'
            }
        }
    }
}
