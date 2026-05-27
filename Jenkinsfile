pipeline {

    agent any

    stages {

        // BUILD STAGE
        stage('Build') {
            steps {
                echo 'Building Application'
            }
        }

        // TEST STAGE
        stage('Test') {
            steps {
                echo 'Running Test Cases'
            }
        }

        // DEPLOY STAGE
        stage('Deploy') {
            steps {
                echo 'Deploying Application'
            }
        }
    }

    post {

        success {
            echo 'Pipeline Success'
        }

        failure {
            echo 'Pipeline Failed'
        }

        always {
            echo 'Pipeline Completed'
        }
    }
}
