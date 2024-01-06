pipeline {
    agent any

    stages {
        stage('Hotfix Branch') {
            steps {
                sh  ' echo "This is hotfix branch code testing" '
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
