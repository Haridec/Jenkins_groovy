pipeline {
    agent any 
    parameters {
        string(name: 'Env', defaultValue: 'dev', description: 'Mention Branch name here?')
    }
    
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
