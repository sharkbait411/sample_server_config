pipeline {
    agent {
        docker {
            image 'python:3.11.3-slim'
        }
    }
    stages {
        stage('Install dependencies') {
            steps {
                sh 'apt update && apt install -y sshpass ansible'
            }
        }
        stage('Run Ansible playbook') {
            steps {
                ansiblePlaybook playbook: 'server_config_playbook.yml', inventory: 'server_inventory.ini'
            }
        }
    }
}