pipeline {
  agent {
    node {
      label 'linux'
    }

  }
  stages {
    stage('building') {
      parallel {
        stage('building') {
          steps {
            echo 'hellow-world'
          }
        }

        stage('parallely') {
          steps {
            sh '''pwd
cd /home/ubuntu/ | ls'''
          }
        }

      }
    }

    stage('test') {
      steps {
        echo 'this is a test script'
      }
    }

  }
}