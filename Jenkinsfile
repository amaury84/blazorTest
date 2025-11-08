pipeline{
    agent any


    stages{
        stage("build"){
            steps{
                bat 'dotnet restore'
                bat 'dotnet build'
            }
        }
        stage("testing"){
            steps{
                bat 'dotnet test blazorTesting'
            }
        }

    }


}