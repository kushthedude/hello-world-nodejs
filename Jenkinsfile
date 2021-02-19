pipeline {
  agent {
    node {
      label 'node-build'
    }

  }
  stages {
    stage('build-app') {
      steps {
        sh '''npm test
'''
      }
    }

    stage('start-app') {
      steps {
        sh 'npm start'
      }
    }

  }
}