pipeline {
    agent any

    stages {
        stage('Build') {
            node {
                echo 'Node: Tamas tries the pipeline'
            }
            steps {
                echo 'outside of Node: Build step'
            }
        }
    }
}