pipeline {
    agent {
        docker { image 'node:20.17-alpine' }
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
