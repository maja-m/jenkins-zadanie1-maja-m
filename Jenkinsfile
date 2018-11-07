pipeline {
    agent { docker { image 'node:9' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}
