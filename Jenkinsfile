pipeline {
  agent {
    docker {
      image 'golang:1.10.1-alpine'
      label 'docker-cloud'
    }
    
  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'hello world'
        sh 'go version'
      }
    }
  }
}