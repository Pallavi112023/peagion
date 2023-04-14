pipeline {
  agent any
  stages {
    stage('pytest') {
      steps {
        sh '''python3 -m pip -V
python3 -m pip freeze'''
      }
    }

  }
}