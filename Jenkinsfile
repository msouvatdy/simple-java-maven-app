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
        sh './home/java.sh'
      }
    }
  }
}