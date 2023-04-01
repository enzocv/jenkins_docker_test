pipeline {
    agent any
    stages {
        stage('Update branch develop') {
            steps {
                sh 'git fetch'
                sh 'git checkout develop'
            }
        }
        stage('Create release branch') {
            steps {
                sh 'git checkout -b release develop'
                sh 'git push -u origin release'
            }
        }
    }
}
