pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'heroku create -jenkins'
                bat 'git add .'
                bat 'git commit -m "test"'
                bat 'git push heroku master'
            }
        }
    }
}
