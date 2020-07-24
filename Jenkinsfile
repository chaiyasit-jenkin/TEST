pipeline {
  agent any
  stages {
    stage('ECHO TEST') {
      parallel {
        stage('ECHO TEST') {
          steps {
            echo 'TEST'
          }
        }

        stage('ECHO TEST2') {
          steps {
            echo 'TEST2'
          }
        }

      }
    }

  }
}