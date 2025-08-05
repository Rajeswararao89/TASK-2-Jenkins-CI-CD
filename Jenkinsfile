pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                script {
                    sh 'docker build -t task-tracker-app .'
                }
            }
        }

        stage('Test API') {
            steps {
                echo 'No automated tests yet, placeholder stage.'
            }
        }

        stage('Deploy Container') {
            steps {
                script {
                    sh 'docker run -d -p 5000:5000 task-tracker-app'
                }
            }
        }
    }
}
