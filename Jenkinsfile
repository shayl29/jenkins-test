pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('pytest') {  
            steps {
                sleep(2)
                sh 'python -m pytest'
                sh 'echo "Done"'
            }   
        }
        stage('someecho') {  
            steps {
                sh 'echo "start"'
                sleep(2)
                sh 'echo "end after sleep"'
            }   
        }
      }
    }
  }
}