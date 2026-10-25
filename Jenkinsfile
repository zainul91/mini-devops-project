
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building Mini DevOps Project'
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
