pipeline {
  agent any
  stages {
    stage('install dependence') {
      steps {
        sh '''npm install --f
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