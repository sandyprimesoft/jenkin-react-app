pipeline {
    agent {
        docker {
            image 'node:6-alpine'
            args: "-p 3000:3000"
        }
    }
    stages {
        stage("build") {
            steps {
                sh "git pull"
                sh "npm install"
            }
        }
    }
}