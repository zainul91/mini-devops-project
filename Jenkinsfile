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
                sh 'test -f index.html'
            }
        }
    }
}
