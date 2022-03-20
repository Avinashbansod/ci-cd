pipeline {
    agent any

    stages {
        stage('checkout ansible repository') {
            steps {
                //git credentialsId: 'avinash_github_new', url: 'git@github.com:Avinashbansod/ansible-prac.git'
                echo 'Hello World!!'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}