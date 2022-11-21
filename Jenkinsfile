pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'build app'
            }
        }
        stage('Test') {
            steps {
                echo 'test app'
            }
        }
        stage('Deploy') {
            steps {
                echo 'deploy app'
            }
        }
    }
         post {
        always {
            emailext body: '', subject: '', to: 'swethap1710@gmail.com'
        }
    }
    
}
