pipeline {
    steps{
        install Docker Pipeline plugin
    }
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
