pipeline {
  agent any
  stages {
    stage('Buzz Build') {
      steps {
        sh 'mvn clean test-compile'
      }
    }

    stage('Buzz Test') {
      steps {
        sh 'mvn surefire:test'
      }
    }

  }
}