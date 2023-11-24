pipeline {
  agent any
  stages {
    stage('install dependence') {
      steps {
        sh '''npm install
'''
      }
    }

    stage('Build') {
      steps {
        sh 'ng build'
      }
    }

  }
}