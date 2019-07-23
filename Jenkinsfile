pipeline {
  agent any
  stages {
    stage('1') {
      steps {
        echo 'Hier Text'
        input(message: 'Eingabe', id: '1', ok: '2', submitter: '3', submitterParameter: '4')
      }
    }
  }
}