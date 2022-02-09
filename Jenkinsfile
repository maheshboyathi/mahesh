pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'mpstat'
      }
    }

    stage('stage2') {
      steps {
        sh 'hostname -I'
      }
    }

  }
}
