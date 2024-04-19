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
        stage('Run server') {
            steps {
                sh 'npm run build'
            }
        }
    }
}

