pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                // In a real scenario, we would run 'npm install'
                sh 'echo "npm install skipped for speed"' 
            }
        }
        
        stage('Test') {
            steps {
                echo 'Testing the application...'
                // Simulating a test
                sh 'echo "All tests passed!"'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                // Simulating deployment
                sh 'echo "Deploying to Docker Hub (Simulated)"'
            }
        }
    }
}