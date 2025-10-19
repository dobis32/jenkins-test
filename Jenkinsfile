pipeline {
    agent { docker { image 'maven:3.9.11-eclipse-temurin-21-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'echo hello world'
                sh 'mvn --version'
            }
        }
    }
}