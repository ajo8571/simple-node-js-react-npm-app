pipeline {
    agent "any"
    
    stages {
        stage('Build') {
            steps {
                pwsh(script: 'echo npm install', returnStdout: true)
            }
        }

    }
}
