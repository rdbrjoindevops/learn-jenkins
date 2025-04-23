pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    echo "Building..."
                }
            }
        }
        // ... other stages
    }
    post {
        always {
            echo "This will always run"
        }
        success {
            echo "Build succeeded!"
        }
        failure {
            echo "Build failed!"
        }
        // ... other post-conditions
    }
}
