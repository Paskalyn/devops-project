pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                sh 'docker build -t devops-app .'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Testing application..."'
            }
        }

        stage('Deploy') {
            steps {
                sh '''
                docker stop app || true
                docker rm app || true
                docker run -d -p 5000:5000 --name app devops-app
                '''
            }
        }
    }
}
