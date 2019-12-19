pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        build 'compile'
      }
    }
    stage('codereview') {
      steps {
        build 'codereview'
      }
    }
    stage('unittest') {
      steps {
        build 'unittest'
      }
    }
    stage('testcoveragecheck') {
      steps {
        build 'cobertura'
      }
    }
  }
}