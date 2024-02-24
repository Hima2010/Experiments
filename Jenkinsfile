node {
    stage('preparation') {
        git 'https://github.com/Hima2010/Experiments.git'
    }
    stage('Build') {
        python hello.py
    }
    stage('Test') {
        ech "this is from test stage"
    }
    stage('Deploy') {
        echo "this is from deploy stage"
    }
}
