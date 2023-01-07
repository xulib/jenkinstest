pipeline {
  agent {
    docker {
      image 'alpine:llatest'
    }

  }
  stages {
    stage('TEST') {
      steps {
        sh 'cat /etc/issue'
      }
    }

  }
}