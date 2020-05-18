node {
    stage('Checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'df1b1f6f-9088-4a68-a1ef-9f345bbdb8b2', url: 'https://github.com/priyanka259/SpringBootOnDocker.git']]])
    }
    stage('Build')
    {
        sh "./mvnw clean install"
    }
}
