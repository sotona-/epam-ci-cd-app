pipeline {
    agent any
    
    stages {
        stage('Ls') {
            steps {
                sh 'ls'
            }
        }
	stage('Ls -la') {
            steps {
                sh 'sseesls 2 -la'
            }
        }
    }
}
