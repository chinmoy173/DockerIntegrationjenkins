pipeline {
  agent {
    docker {
      image 'ubuntu'
    }

  }
  stages {
    stage('Test') {
      steps {
        bat 'node --version'
      }
    }

  }
}