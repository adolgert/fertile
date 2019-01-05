pipeline {
    agent { docker { image 'python:3.6.8' } }
    stages {
        stage('build') {
            steps {
                sh 'echo "Inside the box"'
                sh '''
                python --version
                pwd
                ls -lah
                '''
            }
        }
    }
}
