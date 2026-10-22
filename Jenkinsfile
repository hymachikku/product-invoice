
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Source code checkout completed'
            }
        }

        stage('Build') {
            steps {
                bat 'mvn clean compile'
            }
        }

        stage('Test') {
            steps {
                 bat 'set'
            }
        }

        stage('Package') {
            steps {
                bat 'mvn package'
            }
        }
    }
}
