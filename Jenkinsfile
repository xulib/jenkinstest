pipeline {
  agent {
    docker {
      image 'alpine:latest'
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