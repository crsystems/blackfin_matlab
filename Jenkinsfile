pipeline {
    agent none
    stages {
        stage('build') {
            steps {
                sh 'go version && sudo docker ps'
            }
        }
    }
}
