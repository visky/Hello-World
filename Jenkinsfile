pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                node {
                    echo 'Node: Tamas tries the pipeline'
                }
                echo 'outside of Node: Build step'
            }
        }
    }
}