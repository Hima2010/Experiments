pipeline {
    "agent any"
    stages {
        stage('Install Python') {
            steps {
                script {
                    // Install Python using shell script
                    sh '''
                        #!/bin/bash
                        sudo apt update
                        sudo apt install -y python3
                    '''
                }
            }
        }
        
        stage('Run Python Class') {
            steps {
                script {
                    // Run the Python class
                    sh 'python3 hello.py'
                }
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
