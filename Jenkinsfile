pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                echo "testing my code"
                sh 'python3 -m pytest'
            }
        }
    }
}