pipeline {
    agent any
    triggers {
        githubPush() // Enables GitHub webhook triggering
    }
    stages {
        stage('Hello World') {
            steps {
                echo 'Hello, World!'
            }
        }
    }
}