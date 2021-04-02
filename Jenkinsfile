pipeline {
  agent {
    docker {
      image 'maven:3.3.3'
    }

  }
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