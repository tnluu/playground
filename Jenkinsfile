pipeline {
  agent {
    docker {
      image 'maven'
      args '3.3.3'
    }
    
  }
  stages {
    stage('mystage') {
      steps {
        sh 'mvn -version'
      }
    }
  }
  environment {
    ad = 'ad'
  }
}