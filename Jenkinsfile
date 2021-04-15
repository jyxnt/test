pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            sh 'echo 123'
          }
        }

        stage('test1') {
          steps {
            sh '123'
          }
        }

      }
    }

  }
}