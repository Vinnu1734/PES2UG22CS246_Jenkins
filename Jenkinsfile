pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'g++ hello.cpp -o hello_exec'
            }
        }
        stage('Test') {
            steps {
                
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deployment Successful'
            }
        }
    }
    post {
        failure {
            echo 'Pipeline failed'
        }
    }
}
