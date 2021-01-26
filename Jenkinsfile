pipeline {
    agent any
    stages {
        stage('Build svc1') {
            when {
                changeset "**/svc1/*.*"
            }
            steps {
                sh '''
                    echo "pahit"
                '''
            }
        }
        stage('build svc2') {
            when {
                changeset "**/svc2/*.*"
            }
            steps {
                sh '''
                    echo "manis"
                '''
            }
        }
    }
}
