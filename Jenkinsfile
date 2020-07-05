pipeline {
  agent {
    docker {
      image 'alpine:3.11'
      args '-v /var/run/docker.sock:/var/run/docker.sock'
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