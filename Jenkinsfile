pipeline {
    agent any
    stages {
        stage('Build svc1') {
            when {
                changeset "**/svc1/*.*"
            }
            steps {
                sh '''
                    echo "svc1"
                '''
            }
        }
        stage('build svc2') {
            when {
                changeset "**/svc2/*.*"
            }
            steps {
                sh '''
                    echo "svc2"
                '''
            }
        }
    }
}
