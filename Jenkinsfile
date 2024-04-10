pipeline {
    agent any
    stages {
        stage('Jenkins Account') {
            steps {
                echo 'Account interface'
            }
        }
        stage('Build') { 
            steps {
                sh 'mvn clean install'
            }
        }      
    }
}