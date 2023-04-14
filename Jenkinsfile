pipeline {
  agent any
  stages {
    stage('pytest') {
      steps {
        sh '''python3 -m pip -V
python3 -m pip freeze'''
      }
    }

    stage('group of test') {
      parallel {
        stage('group of test') {
          steps {
            sh '''ls -la
python3 -V'''
          }
        }

        stage('messages') {
          steps {
            echo 'keepcalm'
          }
        }

      }
    }

    stage('test end') {
      steps {
        sh '''ls -la
python3 -V'''
      }
    }

  }
}