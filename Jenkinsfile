pipeline{
    agent any
    stages{
        stage("Welcome"){
            steps{
                echo 'Hellalo'
            }
        }
        stage("Maven Build"){
            steps{
                sh "mvn clean package"
            }
        }
    }
        
}