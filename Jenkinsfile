pipeline {
  agent any
  stages {
    stage('hello') {
      parallel {
        stage('hello') {
          steps {
            sh 'echo \'Hello World\''
          }
        }
        stage('') {
          steps {
            sleep 10
            sh 'echo \'I waited 10 sec\''
          }
        }
      }
    }
    stage('') {
      steps {
        sh 'echo \'This is a test\''
      }
    }
  }
}