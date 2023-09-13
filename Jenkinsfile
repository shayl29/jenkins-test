pipeline {
  agent { docker { image 'python:3.10.5' } }
  stages {
    stage('test') {
      steps {
        sh 'pip install pytest'
        sh 'python -m pytest'
      }   
    }
  }
}