#!groovy

pipeline {
  agent {
    label 'Built-In Node'
  }
  stages {
    stage  ("build") {
      steps {
        withCredentials([usernamePassword(credentialsId: 'apachevmcreds', usernameVariable: 'USERNAME', passwordVariable: 'PASSWORD')]) {
          sh 'echo $PASSWORD'
        }
      }
    }
  }
}
