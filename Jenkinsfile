pipeline {
    agent { docker { image 'php' } }
    stages {
        stage('build') {
            steps {
                sh -c 'php --version'
            }
        }
    }
}
