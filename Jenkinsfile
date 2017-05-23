pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo "hello building"'
      }
    }
    stage('test') {
      steps {
        sh 'echo "test"'
      }
    }
    stage('deploy') {
      steps {
        sh 'echo "time to deploy"'
      }
    }
  }
}