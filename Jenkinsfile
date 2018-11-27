pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
bat 'git init'
bat 'heroku git:remote -a jenkins-zadanie1-maja-m'
                bat 'git add .'
bat 'git commit -am "make it better"'
bat 'git push heroku master'
            }
        }
    }
}
