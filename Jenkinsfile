pipeline {
    agent any
    stages {
        stage('Build'){
            steps {
                echo "Building..."
                sh "touch coolTest"
            }
        }
        stage('Test'){
            steps {
                echo "Testing..."
                sh "ls"
                sh "pwd"
            }
        }
        stage('Deploy'){
            steps {
                echo "Deploying..."
                sh "mv coolTest ~/Test"
            }
        }
    }
}
