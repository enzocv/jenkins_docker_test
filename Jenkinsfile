pipeline {
    agent any
    stages {
        stage('Update branch develop') {
            steps {
                sh 'git checkout develop'
                sh 'git pull'
            }
        }
        stage('Test') {
            steps {
                echo "** EJECUCION DE TEST **"
            }
        }
        stage('SonarQube') {
            steps {
                echo "** EJECUCION DE SonarQube **"
            }
        }
        stage('Fortify') {
            steps {
                echo "** EJECUCION DE Fortify **"
            }
        }
        stage('DEPLOY') {
            steps {
                echo "DEPLOY APP"
            }
        }
    }
}
