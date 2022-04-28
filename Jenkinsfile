pipeline{
    agent { 
        docker { 
            image 'python:3.10.1-alpine' 
        } 
    }
    stages{
        stage('build'){
            steps{
                echo 'Building files'
            }
        }
        stage('test'){
            steps{
                echo 'Running Tests'
                sh 'python labs.py'
            }
        }
    }
}