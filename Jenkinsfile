pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                echo 'Building files'
            }
        }
        stage('Test'){
            steps{
                echo 'Running Tests'
                sh 'python labs.py'
            }
        }
    }
}