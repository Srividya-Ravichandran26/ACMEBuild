pipeline{
    agent any
    
    stages{
        stage('Checkout'){
            steps{
                git 'https://github.com/Srividya-Ravichandran26/ACMEBuild'
            }
        }
        stage('MVN Build'){
            steps{
              bat 'mvn clean install'
            }
        }
    }
}
