pipeline {
  agent {
    node {
      label 'linux'
    }
    
  }
  stages {
    stage('Build') {
      steps {
        sh 'echo"building hex file"'
      }
    }
    stage('Calibrate') {
      steps {
        sh 'echo "calibrating HEX file before the test"'
      }
    }
    stage('HITLoopTest') {
      steps {
        sh 'echo "Testing HEX file"'
      }
    }
  }
}