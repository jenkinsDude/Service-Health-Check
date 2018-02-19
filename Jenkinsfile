pipeline {
  agent any
  stages {
    stage('Check for stopped services') {
      steps {
        build 'PowershellzCopy'
      }
    }
    stage('Report') {
      steps {
        catchError() {
          sh 'hostname'
        }
        
      }
    }
  }
}