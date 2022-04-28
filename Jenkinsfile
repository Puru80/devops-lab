pipeline{
    agent any
    stages{
        stage('Testing'){
            steps{
                echo 'Running Tests'
                bat 'python labs.py'
            }
        }
        stage('Build'){
            steps{
                echo 'Building files'
            }
        }
    }
}