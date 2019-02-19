pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'Helloworld!!!'
          }
        }
        stage('Maven') {
          steps {
            sh 'mvn -version'
          }
        }
      }
    }
  }
}