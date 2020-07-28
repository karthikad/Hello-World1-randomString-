pipeline {
  agent {
    node {
      label 'HelloPipeline'
    }

  }
  stages {
    stage('Build') {
      steps {
        bat 'npm install'
      }
    }

  }
}