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
                sh 'javac Test.java'
                sh 'java Test'
            }
        }
    }
}