pipeline {
  agent any
  stages {
    stage('download') {
      steps {
        echo 'downloadning source code'
      }
    }

    stage('build') {
      steps {
        echo 'build from maven'
      }
    }

    stage('testing') {
      steps {
        echo 'testing_phase'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploying on docker'
        echo 'deploy'
      }
    }

    stage('delivery') {
      steps {
        echo 'delivery'
      }
    }

  }
  environment {
    name = 'download'
  }
}