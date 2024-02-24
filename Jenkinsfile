pipeline {
    agent any
    stages {
        stage('preparation') {
            steps {
                python3 hello.py
                docker{
                    image 'python:2-alphine'
                }
                
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
