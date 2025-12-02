pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building the application..."
                sh 'echo Build Stage Completed'
            }
        }
        stage('Test') {
            steps {
                echo "Running tests..."
                sh 'echo Test Stage Completed'
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying (dummy)..."
                sh 'echo Deployment Stage Completed'
            }
        }
    }
}
