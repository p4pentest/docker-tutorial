pipeline {
    agent any
    stages {
        stage('Docker-Compose Build') {
            steps {
                //sh 'ls -ahl'
                //echo 'Hello'
                sh 'docker-compose -f docker-compose.yml build'
                sh 'docker-compose -f docker-compose.yml up -d'
            }
        }
    }
}
