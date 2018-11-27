pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
bat 'git push heroku ${git rev-parse HEAD}'
            }
        }
    }
}
