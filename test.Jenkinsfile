pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo Building...'
                // Add your build commands here, e.g., mvn package
            }
        }
        stage('Test') {
            steps {
                sh 'echo Testing...'
                // Add your test commands here, e.g., mvn test
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo Deploying...'
                // Add your deployment commands here
            }
        }
    }
}
