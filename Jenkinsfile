node {
    stage('preparation') {
        git 'https://github.com/Hima2010/Experiments.git'
    }
    stage('Build') {
        python hello.py
    }
    stage('Test') {
        ech "this is from Test stage"
    }
    stage('Deploy') {
        echo "this is from Deploy stage"
    }
}
