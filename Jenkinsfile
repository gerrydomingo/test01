pipeline {
  agent any
  stages {
    stage('storage') {
      parallel {
        stage('storage') {
          steps {
            echo 'starting storage'
          }
        }
        stage('database') {
          steps {
            echo 'database'
          }
        }
      }
    }
    stage('check') {
      steps {
        echo 'check'
      }
    }
  }
}