pipeline {
  agent {
    node {
      label 'v4.4.0'
    }

  }
  stages {
    stage('build') {
      steps {
        sh '''npm install
npm run build'''
      }
    }

  }
}