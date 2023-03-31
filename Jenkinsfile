pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Realizar la compilación, pruebas, etc.
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
