pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'ansible-playbook ansible-playbook.yml'
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