pipeline {
    agent any
    stages {
        stage('Build svc1') {
            when {
                changeset "svc1/**"
            }
            steps {
                sh '''
                    echo "svc1"
                '''
            }
        }

        stage('Build svc2') {
            when {
                changeset "svc2/**"
            }
            steps {
                sh '''
                    echo "svc2"
                '''
            }
        }

        stage('Build svc3') {
            when {
                changeset "svc3/**"
            }
            steps {
                sh '''
                    echo "svc3"
                '''
            }
        }

    }
}
