pipeline {
    agent any
    stages{
        stage("Git Checkout"){

           steps{
            git branch: 'main', url: 'https://github.com/manikanta1905/demo-counter-app.git'
           }
        }
        stage("Unit Testiing"){

           steps{
            sh 'mvn test'
           }
        }
    }
}
