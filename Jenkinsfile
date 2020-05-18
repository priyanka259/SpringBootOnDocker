node {
    stage('Checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'f22d1638-8c12-4a71-9806-0717aace91b0', url: 'https://github.com/priyanka259/SpringBootOnDocker.git']]])
    }
}
