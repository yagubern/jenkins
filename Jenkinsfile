pipeline {
agent { label 'docker-slave' }
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
