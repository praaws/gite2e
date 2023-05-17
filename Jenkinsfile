pipeline{
    agent any

    stages{
        stage('Git checkout stage'){
            steps{
                script{
                    git branch: 'main', url: 'https://github.com/praaws/gite2e.git'
                }
            }
        }
    }
}