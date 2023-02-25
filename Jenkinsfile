pipeline {
    agent {
        docker {image 'docker:latest'}
    }
    stages {
        stage('Clone') {
            steps {
               git 'https://github.com/Vinhdevops/Jenkinsfile2.git'
            }
        }
    }
}