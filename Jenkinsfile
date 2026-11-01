pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building the project...'
                sh 'echo Project build started'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing the project...'
                sh 'echo All tests passed'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment completed successfully'
            }
        }
    }

    post {
        success {
            echo 'Pipeline executed successfully!'
        }

        failure {
            echo 'Pipeline execution failed!'
        }
    }
}