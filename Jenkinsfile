pipeline {
  agent any
  stages {
    stage('Git Checkout') {
      steps {
        git(url: 'https://github.com/adamzhanovt/cicd-pipeline', branch: 'main')
      }
    }

  }
}