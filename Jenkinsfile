pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello man How are you?"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
