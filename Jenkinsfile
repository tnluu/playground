pipeline {
  agent any
  stages {
    stage('prepare') {
      steps {
        sh 'echo "Preparing for the day"'
        echo 'pipeline started'
      }
    }
    stage('verify') {
      steps {
        parallel(
          "verify": {
            sh 'echo "ofcourse you must verify"'
            
          },
          "Check": {
            sh 'echo "checking"'
            
          }
        )
      }
    }
    stage('shipit') {
      steps {
        sh 'echo "Let\'s ship it"'
      }
    }
  }
}