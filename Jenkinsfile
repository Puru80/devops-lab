pipeline{
    agent any
    stages {
        stage('Testing') {
            steps {
                echo 'Running Tests'
                sh 'mvn test'
            }
        }
        stage('build') {
            steps {
                echo 'Building files'
                sh 'mav package'
            }
        }
    }
}