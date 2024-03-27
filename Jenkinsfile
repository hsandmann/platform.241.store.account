pipeline {
    agent any
    tools {
        maven 'Maven 3.6.3'
    }
    stages {
        stage('hello') {
            steps {
                echo 'hello world'
            }
        }
        stage('Build') { 
            steps {
                // git url: 'https://github.com/hsandmann/platform.241.store.account'
                // withMaven {
                //     sh 'mvn clean package' 
                // }
                sh 'mvn clean package' 
            }
        }        
    }
}