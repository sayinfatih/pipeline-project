pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Welcome to Pyton code "
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
    }
}