pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'hello world'
        sh 'java -version'
      }
    }
  }
}