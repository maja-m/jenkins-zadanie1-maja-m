pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
sh 'git push heroku ${git rev-parse HEAD}'
            }
        }
    }
}
