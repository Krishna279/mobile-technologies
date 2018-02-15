pipeline {
  agent any
  stages {
    stage('Hello') {
      parallel {
        stage('Hello') {
          steps {
            echo 'Hello World'
            sh 'Execute'
          }
        }
        stage('Build') {
          steps {
            echo 'Hello World'
          }
        }
      }
    }
  }
}