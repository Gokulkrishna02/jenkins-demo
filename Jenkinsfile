pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/Gokulkrishna02/jenkins-demo.git'
            }
        }

        stage('Build') {
            steps {
                echo "Building the project..."
            }
        }

        stage('Test') {
            steps {
                echo "Testing the project..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying the project..."
            }
        }
    }
}
