pipeline {
  agent {
    node {
      label 'production'
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