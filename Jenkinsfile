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
        sh '''cd /var/lib/jenkins
./java.sh'''
      }
    }
    stage('Install maven') {
      steps {
        sh 'echo \'root\' | sudo -S apt install maven -y'
      }
    }
  }
}