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
                sh 'mvn --version'
                bat 'javac Test.java'
                bat 'java Test'
            }
        }
    }
}