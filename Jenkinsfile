pipeline {
  agent any
  stages {
    stage ('build') {
      steps {
        sh 'echo Build'
      }
    }
    stage ('test') {
      steps {
        sh 'echo Test'
        sh 'echo Test passed'
      }
    }
    stage ('development') {
      steps {
        sh 'echo Development'
        sh 'pwd'
        sh 'ls -l'
      }
    }
    stage ('production') {
      steps {
        sh 'echo Production'
      }
    }
  }
}
