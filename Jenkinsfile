pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Pulling source code from GitHub...'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the application...'
                sh 'chmod +x app.sh'
            }
        }

        stage('Test') {
            steps {
                echo 'Running simple test...'
                sh './app.sh'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                echo 'Demo deployment completed successfully.'
            }
        }
    }
}
