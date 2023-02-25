pipeline {
    agent {
        docker {image 'ubuntu:lasted'}
    }
    stages {
        stage('Clone') {
            steps {
               git 'https://github.com/Vinhdevops/Jenkinsfile2.git'
            }
        }
    }
}