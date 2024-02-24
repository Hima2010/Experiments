pipeline {
    agent any
    stages {
        stage('preparation') {
            steps {
                docker{
                image 'python:2-alphine'
                }
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
