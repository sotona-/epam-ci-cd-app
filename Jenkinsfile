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
                sh 'sseesls2 -la'
            }
        }
    }
}
