pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''pwd
ls
date'''
      }
    }

    stage('test') {
      steps {
        echo 'test new'
      }
    }

    stage('add') {
      steps {
        sleep 30
      }
    }

  }
}