pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh '''pwd
ls
date'''
          }
        }

        stage('build1') {
          steps {
            echo 'yes'
          }
        }

      }
    }

    stage('test') {
      steps {
        echo 'test new'
      }
    }

  }
}