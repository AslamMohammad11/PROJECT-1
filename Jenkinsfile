pipeline{
    agent{
        label "slave-1"
    }
    tools {
        jdk "java-17"
        maven "maven-3"
    }
    stages{
        stage("SCM-Checkout"){
            steps{
                git branch: 'main', credentialsId: 'git', url: 'https://github.com/AslamMohammad11/PROJECT-1.git'
            }
            }
        }
    }
