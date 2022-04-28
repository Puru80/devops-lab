pipeline{
    agent any
    
    stages {
        stage('Testing') {
            steps {
                echo 'Running Tests'
            }
        }
        stage('Build') {
            steps {
                echo 'Building jar files...'
                bat 'javac Test.java'
                bat 'java Test'
            }
        }
    }
}