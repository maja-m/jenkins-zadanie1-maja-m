pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
bat 'git show-ref'
                bat 'git commit -m "Initial commit"'
                bat 'git remote -v'
            }
        }
    }
}
