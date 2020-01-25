pipeline {
    agent { docker { image 'arm32v7/python' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                sh 'uname -a'
            }
        }
    }
}
