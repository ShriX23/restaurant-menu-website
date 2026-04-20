pipeline {
    agent any

    triggers {
        githubPush()
    }

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Building restaurant website...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy step (can be Docker/nginx later)'
            }
        }
    }
}