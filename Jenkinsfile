pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('build') {
      steps {
        echo "First Pipeline Job on ${MY_NAME}"
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'ABHISHEK'
  }
}