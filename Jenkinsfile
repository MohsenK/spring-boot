pipeline {
  agent {
    docker {
      image 'gradle:latest'
    }
    
  }
  stages {
    stage('') {
      steps {
        sh 'gradle build'
      }
    }
  }
}