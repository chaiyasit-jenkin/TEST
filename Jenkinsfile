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

    stage('TEST_ARTIFACT') {
      steps {
        archiveArtifacts(artifacts: 'TEST', fingerprint: true)
      }
    }

  }
}