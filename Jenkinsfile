pipeline {
    agent { docker 'maven:3.5.3' }
    stages {
        stage('build') {
            steps {
                bat 'mvn --version'
            }
        }
    }
}
