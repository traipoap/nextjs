pipeline {
    agent any
    stages {
        stage('Check') {
            steps {
                sh "npm install"
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

