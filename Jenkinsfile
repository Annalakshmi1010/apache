#!groovy

pipeline {
	agent {
		label 'Built-In Node'
	}
	stages {
		stage {
			steps {
				withCredentials([usernamePassword(credentialsId: 'apachevmcreds', usernameVariable: 'USERNAME', passwordVariable: 'PASSWORD')]) {
				 sh 'echo $PASSWORD'
        }
			}
		}
	}
}
