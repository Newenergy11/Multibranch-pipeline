pipeline {
    agent any

    stages {
        stage('Main Branch') {
            steps {
                sh  ' echo "This is main branch code testing" '
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
