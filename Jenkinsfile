#!groovy

pipeline {
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
