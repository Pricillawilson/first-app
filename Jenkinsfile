pipeline{
    agent any
    stages{
        stage("Git Checkout"){
            steps{
                git credentialsId:'github' ,url:'https://github.com/Pricillawilson/first-app.git',branch:'main'
            }
        }
    }
        
}