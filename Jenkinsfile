pipeline {
  agent any
  stages {
    stage('Check for stopped services') {
      steps {
        powershell(script: 'PowershellzCopy', returnStatus: true, returnStdout: true)
        build 'PowershellzCopy'
      }
    }
  }
}