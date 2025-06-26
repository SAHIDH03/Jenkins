pipeline {
    agent any
 
    stages {
        stage('Checkout') {
            steps {
                echo 'Cloning the repo...'
            }
        }
 
        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }
 
        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'date'
            }
        }
 
        stage('Info') {
            steps {
                sh 'uname -a'
            }
        }
 
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
            }
        }
    }
}
