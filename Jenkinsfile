pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        sh 'echo \'Hello World\''
      }
    }
    stage('Test') {
      steps {
        sh 'echo \'This is a test\''
      }
    }
    stage('Install java') {
      steps {
        sh '$echo root | sudo -S apt-get update -y'
        sh 'apt install openjdk-11-jdk -y'
      }
    }
  }
}