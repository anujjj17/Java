pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/anujjj17/Java.git'
            }
        }

        stage('Build') {
            steps {
                sh 'javac Calculator.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Calculator'
            }
        }
    }
}
