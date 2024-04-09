pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'npm run dev'
            }
            steps {
                sh 'sleep 100'
            }
        }
    }
}
