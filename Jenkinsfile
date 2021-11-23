pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'This is build $BUILD_NUMBER of job called $DEMO'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}