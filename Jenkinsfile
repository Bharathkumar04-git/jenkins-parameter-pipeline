pipeline {
    agent any
    parameters {
        string(name: 'ENVIRONMENT', defaultValue: 'staging', description: 'Target environment to build for')
    }
    stages {
        stage('Show Parameter') {
            steps {
                echo "Selected environment: ${params.ENVIRONMENT}"
            }
        }
        stage('Build for Environment') {
            steps {
                echo "Running build steps for ${params.ENVIRONMENT} environment..."
            }
        }
    }
}
