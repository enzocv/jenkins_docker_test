pipeline {
    agent any
    stages {
        stage('Create release branch') {
            steps {
                sh 'git checkout -b release develop'
                sh 'git push -u origin release'
            }
        }
    }
}
