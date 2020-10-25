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
                sh 'sse esl s 2 -la'
            }
        }
    }
}
