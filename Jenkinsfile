pipeline {
    agent { docker 'openjdk:8-jre' }

    stages {
        stage('Build') {
            
            steps {
                echo 'Build step'
                sh 'javac HelloWorld.java'
                sh 'java HelloWorld'
            }
        }
    }
}