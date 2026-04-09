pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/nikhil-stackly/my-pipeline.git'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Building application..."'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Running tests..."'
            }
        }
    }
}
