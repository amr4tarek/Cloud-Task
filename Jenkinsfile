pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git clone 'https://github.com/amr4tarek/cloud-2'
            }
        }

        stage('Execute bat file') {
            steps {
                bat "CloudTask.bat"
            }
        }
    }
}