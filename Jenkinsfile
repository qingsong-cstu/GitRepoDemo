pipeline {
    agent any
    
    stages {
        stage('Build') { 
            steps {
                sh "echo Build"
                sh "hostname"
                sh "uname -a"
            }
        }
        stage('Test') { 
            steps {
                sh "echo Test"
            }
        }
        stage('Deploy') { 
            steps {
                sh "echo Deploy" 
            }
        }
    }
}
