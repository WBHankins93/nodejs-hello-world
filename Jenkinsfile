pipeline {
    agent { docker { image 'node:13.12-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'npm install'
            }
        }
    }
}