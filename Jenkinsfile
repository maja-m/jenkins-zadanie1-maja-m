pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'echo "Test"'
                bat 'git push heroku master'
            }
        }
    }
}
