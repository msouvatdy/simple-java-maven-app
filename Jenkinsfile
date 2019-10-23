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
        sh 'sudo apt update -y'
        sh 'sudo apt install openjdk-11-jdk -y'
      }
    }
  }
}