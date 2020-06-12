pipeline {
  agent {
    node {
      label 'jenkins-slave'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'npm install'
      }
    }

  }
}