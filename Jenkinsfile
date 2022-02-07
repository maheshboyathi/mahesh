pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'du -h'
      }
    }

    stage('stage2') {
      steps {
        sh 'hostname -I'
      }
    }

  }
}
