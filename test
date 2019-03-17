pipeline {
    agent { docker { image 'maven:3.3.2' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
