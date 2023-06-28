pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'echo PWD'
            sh 'echo $PWD'
          }
        }

        stage('Test') {
          steps {
            echo 'hello world'
          }
        }

      }
    }

  }
}