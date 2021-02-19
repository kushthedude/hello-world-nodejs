pipeline {
  agent {
    node {
      label 'master'
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
