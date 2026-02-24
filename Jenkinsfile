pipeline {
    agent any // Tells Jenkins to allocate any available agent (executor and workspace)

    stages {
        stage('Build') {
            steps {
                // Commands to compile code, install dependencies, or package the app
                sh 'echo "Building the application..."'
                //sh 'make sampleapp' 
            }
        }

        stage('Test') {
            steps {
                // Commands to run unit tests, integration tests, or quality checks
                sh 'echo "Running tests..."'
                //sh './testcasescript' 
            }
        }

        stage('Deploy') {
            steps {
                // Commands to deploy the tested application to a server/environment
                sh 'echo "Deploying to server..."'
                //sh './deployscript'
            }
        }
    }
}
