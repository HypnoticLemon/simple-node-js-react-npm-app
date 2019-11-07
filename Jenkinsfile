pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''nodejs(nodeJSInstallationName: \'nodejs\') {
       sh \'npm install\'}'''
        }
      }

    }
  }