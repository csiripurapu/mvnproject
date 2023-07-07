pipeline {
  agent any
  stages {
    stage('Git Checkout') {
      parallel {
        stage('Git Checkout') {
          steps {
            git(url: 'https://github.com/csiripurapu/mvnproject', branch: 'main', credentialsId: 'ckgithub')
          }
        }

        stage('') {
          steps {
            sh '''#!/bin/bash

cat /etc/os-release
hostname'''
          }
        }

      }
    }

  }
}