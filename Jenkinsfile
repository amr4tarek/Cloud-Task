pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/amr4tarek/Cloud-Task.git'
            }
        }

        stage('Execute bat file') {
            steps {
                bat "CloudTask.bat"
            }
        }
    }
}