pipeline {
    agent any

    stages {
        stage('Build') {
            
            steps {
                echo 'Build step'
                bat 'javac HelloWorld.java'
                bat 'java HelloWorld'
            }
        }
    }
}