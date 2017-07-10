pipeline {
    agent any

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