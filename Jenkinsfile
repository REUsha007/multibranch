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
         stage('chechkin') {
            steps {
                sh 'echo chechkin jenkins file'
            }
        }
         stage('out') {
            steps {
                sh 'echo out jenkins file'
            }
        }
    }
}
