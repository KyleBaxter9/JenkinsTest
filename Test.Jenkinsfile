pipeline {
    agent { node { label "Test" } }

    stages {
        stage('Test Agent') {
            steps {
                bat "cd C:\\"
                bat "dir"
            }
        }
    }
    post {
        always {
            cleanWs()
        }
    }
}
