pipeline {
  agent any
  stages {
    stage('Print JDK') {
      steps {
        sh 'java -version'
      }
    }
    stage('Print Ruby') {
      steps {
        sh 'ruby -version'
      }
    }
  }
}