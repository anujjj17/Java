pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/your-username/repo-name.git'
            }
        }

        stage('Build') {
            steps {
                sh 'javac Calculator.java'
            }
        }

        stage('Test') {
            steps {
                sh 'java Calculator'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment step (Define as needed)'
            }
        }
    }
}
