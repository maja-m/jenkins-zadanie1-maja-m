pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'echo "Test"'
                
                bat 'git checkout master'
                bat 'git pull'
                bat 'git add .'
                bat 'git commit -m "commit"'
                bat 'git push heroku master'
            }
        }
    }
}
