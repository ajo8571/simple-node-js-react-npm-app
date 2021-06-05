pipeline {
    agent "any"
    
    stages {
        stage('Build') {
            steps {
                powershell(script: 'echo npm install', returnStdout: true)
            }
        }

    }
}
