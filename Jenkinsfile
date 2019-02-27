pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'go version && sudo docker ps'
            }
        }
    }
}
