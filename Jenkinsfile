/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    tools {
      go '1.21.1'
    }
    stages {
        stage('build') {
            steps {
                sh 'go version'
            }
        }
    }
}