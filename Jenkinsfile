pipeline{
    agent any
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