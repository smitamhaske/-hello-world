pipeline {
    agent { docker { image 'node:11.3.0' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}
