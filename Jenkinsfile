pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'Building'
        sh 'echo $text'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing'
      }
    }
  }
  environment {
    text = 'this is the text'
  }
}