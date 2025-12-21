pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                cleanWs()
                sh 'echo "This is from Build stage"'
                sh 'whoami'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Test is done"'
            }
        }
    }
}
