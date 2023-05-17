@Library('your-shared-library') _


pipeline{
    agent any

    stages{
        stage('Git checkout stage'){
            steps{
                script{
                    checkoutGit(
                        repositoryUrl = "https://github.com/praaws/gite2e.git",
                        branch = "main"
                    )
                }
            }
        }
    }
}