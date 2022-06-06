pipeline {
    agent any

    stages {
        stage('get from git') {
            steps {
                git branch: 'main', credentialsId: 'gitvector', url: 'git@github.com:Danil054/vector-role.git'
            }
        }
        stage('molecule_test') {
            steps {
                sh 'pip3 install --user "molecule==3.4.0" "molecule_docker"'
                sh 'molecule --version'
                sh 'molecule test'
            }
        }
    }
}
