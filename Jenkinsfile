pipeline {
  agent any
  stages {
    stage('1') {
      steps {
        echo 'Hier Text'
        input(message: 'Eingabe', id: '1')
      }
    }
    stage('a') {
      parallel {
        stage('a') {
          steps {
            sh 'echo "hallo"'
          }
        }
        stage('') {
          steps {
            waitUntil() {
              echo 'Eingabbbbbe'
            }

          }
        }
      }
    }
  }
}