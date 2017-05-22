pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        parallel(
          "build": {
            sh 'print "building SW"'
            sleep 2
            
          },
          "code analysis": {
            sh 'echo "scanning the code"'
            
          }
        )
      }
    }
    stage('test') {
      steps {
        sh 'echo "tested"'
      }
    }
    stage('Deploy') {
      steps {
        sh 'echo "deployed"'
      }
    }
  }
}