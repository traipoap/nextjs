pipeline {
    agent any
    stages {
        stage('Check') {
            steps {
                sh "npm version"
            }
        }
        stage('Build') {
            steps {
                sh 'npm run dev'
            }
        }
    }
}

