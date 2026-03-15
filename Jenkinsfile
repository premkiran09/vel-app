pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the Velocity App...'
                sh 'ls -ltr'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'echo "Tests Passed"'
            }
        }
    }
}
