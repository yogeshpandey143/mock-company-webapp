pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    // TODO: Add build steps here
                    sh './gradlew assemble'
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    // TODO: Add test steps here
                    sh './gradlew test'
                }
            }
        }
    }
}