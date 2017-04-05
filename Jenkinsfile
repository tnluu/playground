pipeline {
  agent any
  stages {
    stage('prepare') {
      steps {
        parallel(
          "prepare": {
            sh 'echo "Preparing for the day"'
            echo 'pipeline started'
            
          },
          "Check": {
            sh 'echo "Checking if everything okay"'
            
          }
        )
      }
    }
    stage('verify') {
      steps {
        sh 'echo "ofcourse you must verify"'
      }
    }
    stage('shipit') {
      steps {
        sh 'echo "Let\'s ship it"'
      }
    }
  }
}