 pipeline {
    agent any

    stages {
        stage('Hello') {
                    steps {
                        echo 'Hello world!'
                    }
        }
        stage('Check node version ') {
                    steps {
                        bat "node --version"
                    }
        }
    }
 }