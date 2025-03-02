pipeline {
    agent any
    stages {
        stage('Check SonarQube Scanner Path') {
            steps {
                script {
                    sh 'which java'  // This will check if sonar-scanner is in the PATH
                }
            }
        }
    }
}
