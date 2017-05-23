pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo "helloworld"'
        sleep 2
      }
    }
    stage('test') {
      steps {
        sh 'echo "testing"'
      }
    }
    stage('deploy') {
      steps {
        sh 'echo "deplyoing"'
      }
    }
  }
}