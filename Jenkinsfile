pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'touch readme'

                bat 'git add .'

bat 'git commit -m "test"'

bat 'git push heroku master'
            }
        }
    }
}
