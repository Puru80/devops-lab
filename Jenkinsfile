pipeline{
    agent any
    stages{
        stage('Testing'){
            steps{
                echo 'Running Tests'
                bat 'python3 labs.py'
            }
        }
        stage('Build'){
            steps{
                echo 'Building files'
            }
        }
    }
}