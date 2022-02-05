pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                echo 'This is run step'
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
    }
}
