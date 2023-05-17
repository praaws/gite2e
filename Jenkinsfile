@Library('your-shared-library') _


pipeline{
    agent any

    stages{
        stage('Git checkout stage'){
            steps{
                script{
                    Checkout(
                        repositoryUrl = "https://github.com/praaws/gite2e.git",
                        branch = "main"
                    )
                }
            }
        }
    }
}