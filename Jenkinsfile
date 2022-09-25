pipeline {
  agent any
  stages {
    stage('Build/Shell Script') {
      steps {
        sh 'echo "This is Build Number"'
      }
    }

    stage('Test/shell script') {
      steps {
        sh 'echo "testing phase"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}