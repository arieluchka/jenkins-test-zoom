pipeline {
    agent any


    stages {
        stage("hello") {
            steps {
                echo 'hello world'
            }
        }
        stage("whats in the file") {
            steps {
                sh "cat main.py"
            }
        }

    }
}