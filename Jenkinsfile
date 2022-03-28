#!groovy

pipeline {
  agent {
    label 'master'
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
