pipeline {
    agent { docker { image 'golang' } }
    stages {
        stage('build') {
            steps {
                sh 'go version && sudo docker ps'
            }
        }
    }
}
