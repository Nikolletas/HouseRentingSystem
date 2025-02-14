pipeline{
    agent any
    stages{
        stage('NPM Install'){
            steps{
                bat 'dotnet build'
            }  
        }
        stage('Run tests'){
            steps{
                bat 'dotnet test'
            }
        }
    }
}