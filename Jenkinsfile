pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'This is Build ${BUILD_NUMBER} of the job ${DEMO}'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}