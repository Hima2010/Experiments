pipeline {
    agent any
    stages {
        stage('preparation') {
            script {
                    // Install Python using shell script
                    sh '''
                        #!/bin/bash
                        sudo apt update
                        sudo apt install -y python3
                        python3 hello.py
                    '''
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
