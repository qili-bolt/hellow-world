/* Requires the Docker Pipeline plugin */
pipeline {
    agent {
      label 'docker' 
    }
    stages {
        stage('build') {
            steps {
                sh 'go version'
            }
        }
    }
}