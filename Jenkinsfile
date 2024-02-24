pipeline {
    agent any
    stages {
        stage('preparation') {
            docker{
                image 'python:2-alphine'
            }
            steps {
                sh 'python hello.py'
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
