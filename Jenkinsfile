pipeline {
    agent any
    tools {
        git 'Default' 
    }
    stages {
        stage('clone the repo') {
            steps {
                git "https://github.com/priyanka259/SpringBootOnDocker.git" 
            }
        }
        stage('Build') {
            steps {
                sh "./mvnw clean install"
            }
        }
    }
}
