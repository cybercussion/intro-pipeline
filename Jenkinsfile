pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello Again!'
        sh 'java -version'
      }
    }
  }
}