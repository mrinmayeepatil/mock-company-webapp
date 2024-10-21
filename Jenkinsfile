pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Running on Jenkins agent'
                sh './gradlew assemble'
            }
        }

        stage('Test') {
            steps {
                sh './gradlew test'
            }
        }
    }
}


