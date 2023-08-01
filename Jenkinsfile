pipeline{
    agent{
        label 'node1'
    }
    tools {
        maven 'mvn393'
    }
    stages{
        stage("Maven Build"){
            steps{
                sh "mvn deploy"
            }
        }
    }
}
