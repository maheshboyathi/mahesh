pipeline() {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'ifconfig'
      }
    }

    stage('stage2') {
      steps {
        sh 'hostname -I'
      }
    }

  }
}
