pipeline {
    agent any
    stages {
        stage('Install') {
            steps {
                sh "npm install"
            }
        }
        stage('Build') {
            steps {
                sh 'npm run build'
            }
        }
        stage('Run server') {
            steps {
                sh 'npm run dev'
            }
        }
    }
}

