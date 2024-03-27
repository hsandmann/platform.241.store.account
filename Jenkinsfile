pipeline {
    agent any
    tools {
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