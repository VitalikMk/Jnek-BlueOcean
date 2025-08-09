pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('TEST') {
      steps {
        sh 'apk add --no-cache npm'
        sh 'npm install'
      }
    }

  }
}