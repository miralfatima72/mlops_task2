pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                bat 'pip install -r requirements.txt'
            }
        }
        
        stage('Test') {
            steps {
                bat 'python test_test.py'
            }
        }
        
        stage('Deploy') {
            steps {
                bat 'echo deployed'
            }
        }
    }
}