pipeline {
    agent any
    stages {
        stage('Check SonarQube Scanner Path') {
            steps {
                script {
                    sh 'echo $SONAR_RUNNER_HOME'
                }
            }
        }
    }
}
