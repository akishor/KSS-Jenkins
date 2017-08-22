pipeline {
  agent {
    docker {
      image 'centos:latest'
    }
    
  }
  stages {
    stage('Stag1') {
      steps {
        echo 'Hello Centos'
      }
    }
    stage('stag2') {
      steps {
        echo 'Stag2'
      }
    }
  }
}