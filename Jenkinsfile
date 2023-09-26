pipeline{
    agent any
    Environment{
        path="/apache-maven-3.9.4/bin:$path"
    }
    stages{
        stage("Git Checkout"){
           steps{
            git credentialsId: '874a591e-d9fb-4bec-b940-11b3b6fe77ef', url: 'https://github.com/Saipriyanka30/build_deploy.git'
           }
        }
        stage("mvn build"){
            steps{
                sh "mnv clean package"

    }
}
