pipeline {
  agent any
  stages {
    stage('Build/Print Message') {
      parallel {
        stage('Build/Print Message') {
          steps {
            echo 'Hi World'
          }
        }

        stage('Test') {
          steps {
            bat 'java HelloWord.java'
          }
        }

      }
    }

  }
}