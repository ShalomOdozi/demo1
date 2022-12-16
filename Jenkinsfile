pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        sh 'echo "This is the $BUILD_NUMBER of demo $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}