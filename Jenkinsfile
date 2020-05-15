pipeline {
    agent any
    tools {
        git 'Default' 
    }
    stages {        
        stage('Build') {
            steps {
                sh "./mvnw clean install"
            }
        }
    }
}
