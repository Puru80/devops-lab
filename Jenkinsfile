Pipeline{
    agent only
    Stages{
        Stage('Testing'){
            Steps{
                echo 'Running Tests'
                bat 'python labs.py'
            }
        }
        Stage('Build'){
            Steps{
                echo 'Building files'
            }
        }
    }
}