pipeline {
    agent any

    stages {
        stage('Development Branch') {
            steps {
                sh  ' echo "This is development branch code testing........." '
            }
        }
        stage('sprint1') {
            steps {
                 sh ' echo "sprint application..." '
            }
        }
        stage("Deploy application") {
            steps {
                 sh ' echo "Deploying application...." '
            }
        }
    }
}
