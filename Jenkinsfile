pipeline {
    agent {
        docker {
            image: "node:alpine"
            args: "-p 3000:3000"
        }
    }
    stages {
        stage("build") {
            steps {
                sh "sudo npm install"
            }
        }
    }
}