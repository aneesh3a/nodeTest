pipeline {
  agent {
    docker {
      image 'docker'
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