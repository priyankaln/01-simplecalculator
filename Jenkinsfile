pipeline {
  agent {
    node {
      label 'slave1'
    }
    
  }
  stages {
    stage('checkout') {
      steps {
        git(url: 'git@github.com:priyankaln/01-simplecalculator.git', branch: 'master')
      }
    }
  }
}