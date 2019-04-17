pipeline {
    agent any

    environment {
        DISABLE_AUTH = 'true'
        DB_ENGINE    = 'sqlite'
        PATH         = '$PATH:/usr/local/bin'
    }

    stages {
        stage('Build') {
            steps {
                sh 'printenv'
            }
        }
    }
}