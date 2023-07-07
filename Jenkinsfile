pipeline {
  agent any
  stages {
    stage('Git Checkout') {
      steps {
        git(url: 'https://github.com/csiripurapu/mvnproject', branch: 'main', credentialsId: 'ckgithub')
      }
    }

  }
}