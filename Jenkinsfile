pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
bat 'git add --all'
                bat 'git commit -m "Initial comment"'
                bat 'git push heroku master'
            }
        }
    }
}
