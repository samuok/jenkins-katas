pipeline {
  agent any
  stages {
    stage('Say hello') {
      parallel {
        stage('Say hello') {
          steps {
            sh 'echo "hello world"'
          }
        }

        stage('build app') {
          steps {
            sh 'touch teksti.txt'
          }
        }

      }
    }

  }
  environment {
    Say_hello = ''
  }
}