/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    stages {
        stage('build') {
            steps withEnv(PATH='$PATH:/usr/local/go/bin') {
                sh 'echo $PATH'
            }
        }
    }
}