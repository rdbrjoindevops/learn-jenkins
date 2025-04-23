pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    echo "This is build"
                }
            }
        }
    }
}
  post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
