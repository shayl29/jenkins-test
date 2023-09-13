pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'pip3 install pytest'
        sh 'python3 -m pytest'
      }   
    }
  }
}