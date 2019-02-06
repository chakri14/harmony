pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat(script: 'cd myapp;mvn clean install', returnStatus: true)
      }
    }
  }
}