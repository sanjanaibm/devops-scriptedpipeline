pipeline {
  agent any
  stages {
    stage('Build/Shell Script') {
      steps {
        sh 'echo "This is Build number ${BUILD_NUMBER} and env variable ${DEMO}"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}