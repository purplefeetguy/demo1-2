pipeline {
  agent any
  stages {
    stage('stage 1') {
      steps {
        sh 'echo "This is build $BUILD_NUMBER of $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}