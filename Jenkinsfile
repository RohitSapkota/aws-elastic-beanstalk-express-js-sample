pipeline {
	agent {
		docker {
			image 'node:16.3.0-alpine'
			args '-p 3000:3000'
		}
	}
	stages {
		stage('Build') {
			steps {
				sh 'npm install -save'
			}
		}
	}
}
