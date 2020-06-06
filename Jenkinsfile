pipeline {
  agent any
  stages {
    stage('print') {
      steps {
        sh '''echo $BUILD_NUMBER
echo $JENKINS_URL'''
      }
    }

  }
}