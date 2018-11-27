pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
bat 'git checkout master'
                bat 'git branch tmp c18550406783a1b387c9d79718ca43bacf36c659'
                bat 'git merge tmp'
            }
        }
    }
}
