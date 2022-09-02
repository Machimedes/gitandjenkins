pipeline {
    agent any
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') {
            steps {
                echo 'build'
            }
        }
        stage('Test') {
            steps {
                sh 'echo test'
            }
        }
    }
}