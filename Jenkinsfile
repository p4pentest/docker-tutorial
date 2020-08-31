pipeline {
    agent any
    stages {
        stage('Docker-Compose Build') {
            steps {
                //sh 'ls -ahl'
                //echo 'Hello'
                sh 'dock-compose -f docker-compose.yml build'
                sh 'dock-compose -f docker-compose.yml up -d'
            }
        }
    }
}
