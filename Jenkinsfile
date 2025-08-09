pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'node:10-alpine'
    }

  }
  stages {
    stage('TEST') {
      steps {
        sh 'echo "Hello worl"'
      }
    }

  }
}