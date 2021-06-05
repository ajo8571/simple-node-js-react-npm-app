pipeline {
    agent "any"
    
    stages {
        stage('Build') {
            steps {
                pwsh(script: 'npm install' returnStdout: true)
            }
        }

    }
}
