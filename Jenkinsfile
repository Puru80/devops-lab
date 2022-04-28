pipeline{
    agent any
    stages {
        stage('Testing') {
            steps {
                echo 'Running Tests'
                sh 'mvn test'
            }
        }
        stage('Build') {
            steps {
                echo 'Building jar files...'
                sh 'mvn package'
            }
        }
    }
}