pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
        stage('Testing') {
            steps {
                echo "this stage is used for Testing" 
            }
        }
    }
}
