pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build step'
                sh 'javac HelloWorld.class'
                sh 'java HelloWorld'
            }
        }
    }
}