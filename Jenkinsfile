pipeline {
  agent any
  stages {
    stage('') {
      steps {
        powershell(returnStdout: true, script: 'test.ps1')
      }
    }

  }
  environment {
    dev = 'testdev'
  }
}