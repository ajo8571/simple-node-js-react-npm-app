pipeline {
    agent "any"
    
    stages {
        stage('Build') {
            steps {
                echo 'npm install...'
                powershell(script: 'npm install')
                echo 'yarn build...'
                powershell(script: 'yarn build')
            }
        }

        stage('Test') {
            steps {
                echo 'running jest tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Built & Tested succesfully!'
                echo 'Deploying...'
            }
            
        }

    }
}
