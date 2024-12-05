pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Pull code from GitHub
                git branch: 'main', url: 'https://github.com/your-username/your-repo.git'
            }
        }

        stage('Build') {
            steps {
                // Add build commands
                echo 'Building the application...'
                sh 'echo Build completed' // Replace with actual build commands
            }
        }

        stage('Test') {
            steps {
                // Add test commands
                echo 'Running tests...'
                sh 'echo Tests completed' // Replace with actual test commands
            }
        }

        stage('Deploy') {
            steps {
                // Add deployment commands
                echo 'Deploying the application...'
                sh 'echo Deployment completed' // Replace with actual deployment commands
            }
        }
    }

    post {
        always {
            echo 'Pipeline completed!'
        }
    }
}
