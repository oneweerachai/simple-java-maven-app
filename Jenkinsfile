pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'echo build....' 
            }
        }
        stage('Test') {
            steps {
                sh 'echo Test'
            }
            post {
                always {
                    sh 'echo Post..'
                }
            }
        }
        stage('Deliver') {
            steps {
                sh 'echo Deliver....'
            }
        }
    }
}