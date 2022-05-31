pipeline{
    agent any

    environment{
        PATH = "/usr/share/maven/bin:$PATH"
    }
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