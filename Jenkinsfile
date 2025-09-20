// Jenkinsfile
pipeline {
    agent any
    stages {
        stage('Build & Test') {
            steps {
                script {
                    // Echo the branch name to see which pipeline is running
                    echo "Building branch: ${env.BRANCH_NAME}"
                    
                    // Use Maven to compile the project
                    sh 'mvn clean install'
                }
            }
        }
    }
}
