pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building project...'
                sh 'javac HelloWorld.java'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'java HelloWorld'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
            }
        }
    }
}
