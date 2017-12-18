pipeline {
  agent {
    node {
      label 'master'
    }
    
  }
  stages {
    stage('checkout') {
      steps {
        git(url: 'git@github.com:priyankaln/02-Calculator.Demo.git', branch: 'master')
      }
    }
  }
}