pipeline {
    agent any
    stages {
        stage('preparation') {
            steps {
                sudo apt-get install python3
                python3 hello.py     
            }
        }
        stage('Build') {
            steps {
                echo "building"
            }
        }
        stage('Test') {
            steps {
                echo "testing"
            }
        }
        stage('Deploy') {
            steps {
                echo "deploy"
            }
        }
    }
}
