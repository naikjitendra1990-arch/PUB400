pipeline {
    agent any

    stages {
        stage('Show Files') {
            steps {
                bat 'dir'
            }
        }

        stage('Display CL Source') {
            steps {
                bat 'type testcl.cl'
            }
        }
    }
}
