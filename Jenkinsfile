pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Hello'
          }
        }
        stage('Post Build') {
          steps {
            echo 'Post Build'
          }
        }
      }
    }
  }
}