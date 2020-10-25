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
                sh 'sseesl s 2 -la'
            }
        }
    }
}
