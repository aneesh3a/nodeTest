pipeline {
  agent {
    docker {
      image 'alpine:3.11'
    }

  }
  stages {
    stage('Test') {
      steps {
        sh 'node --version'
      }
    }

  }
}