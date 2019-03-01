pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'master', url: 'https://github.com/anilkchandu/CreditCruse.git'
                
                echo 'checkout..'
            }
        }
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Review') {
            steps {
                echo 'Review the code....'
            }
        }
        
        stage('Repository') {
            steps {
                echo 'the code repository....'
            }
        }
        
        stage('deploy') {
            steps {
                echo 'Deploy the code....'
            }
        }
    }
}