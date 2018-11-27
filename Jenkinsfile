pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'heroku git:remote -a jenkins-zadanie1-maja-m'
                bat 'git add .'
                bat 'git commit -m "test"'
                bat 'git push heroku master'
            }
        }
    }
}
