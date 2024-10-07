pipeline {
    agent {
        label 'docker_agent1'
        docker { image 'docker pull node:20.17-alpine' }
    }
    stages {
        stage('checking') {
            steps {
                echo 'Hello World'
                sh'node --version'
            }
        }
    }
}
