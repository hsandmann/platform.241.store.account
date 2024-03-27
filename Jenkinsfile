pipeline {
    // agent any
    agent { docker { image 'maven:3.9.6-eclipse-temurin-17-alpine' } }
    // tools {
    //     maven 'Maven 3.9.6'
    // }
    stages {
        stage('hello') {
            steps {
                echo 'hello world'
            }
        }
        stage('Build') { 
            steps {
                sh 'mvn clean package'
            }
            // steps {
            //     git url: 'https://github.com/hsandmann/platform.241.store.account'
            //     withMaven {
            //         sh 'mvn clean package' 
            //     }
            //     // sh 'mvn clean package' 
            // }
        }        
    }
}