pipeline {
    agent any

    stages {
        stage('Install Python') {
            steps {
                script {
                    sh '''
                    apt-get update && apt-get install -y python3 python3-pip
                    '''
            }
        }
    }
}
