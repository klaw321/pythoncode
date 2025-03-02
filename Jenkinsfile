pipeline {
    agent any
    stages {
        stage('Check SonarQube Scanner Path') {
            steps {
                script {
                    sh 'which sonar-scanner'  // This will check if sonar-scanner is in the PATH
                }
            }
        }
    }
}
