pipeline {
    agent any
    stages {
        stage('Jenkins Account') {
            steps {
                echo 'Jenkins Account'
            }
        }
        stage('Build') { 
            steps {
                sh 'mvn clean install'
            }
        }      
    }
}