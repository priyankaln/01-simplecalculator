pipeline {
  agent {
    node {
      label 'master'
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