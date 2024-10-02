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
      parallel {
        stage('test') {
          steps {
            echo 'test new'
          }
        }

        stage('test par') {
          steps {
            echo 'test par'
          }
        }

      }
    }

    stage('deploy') {
      parallel {
        stage('deploy') {
          steps {
            echo 'deploy'
          }
        }

        stage('add') {
          steps {
            sleep 30
          }
        }

      }
    }

  }
}