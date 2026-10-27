
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building Mini DevOps Project'
                bat 'docker build -t mini-devops-app:1.0 .'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Mini DevOps Project'
                bat 'if exist index.html (echo HTML file found) else (exit 1)'
            }
        }
    }
}
