pipeline {
    agent any

    stages {
        stage('checkout ansible repository') {
            steps {
                git credentialsId: 'avinash_github_new', url: 'git@github.com:Avinashbansod/ansible-prac.git'
                //echo 'Hello World!!'
            }
        }
        stage('run ansible-playboook') {
            steps {
                ansiblePlaybook credentialsId: 'ansible_key', installation: 'ansible-plugin', inventory: 'hosts', playbook: 'main.yaml', sudoUser: null
            }
        }
    }
}