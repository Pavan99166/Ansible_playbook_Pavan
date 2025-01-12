pipeline {
    agent { label 'ansible' }

    stages {
        stage('install grafana') {
            steps {
               sh "sudo ansible-playbook /home/ubuntu/grafanainstall.yml"
            }   
           }
           }
}
