pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        git(url: 'https://github.com/csiripurapu/mvnproject', branch: 'main', credentialsId: 'ckgithub')
      }
    }

  }
}