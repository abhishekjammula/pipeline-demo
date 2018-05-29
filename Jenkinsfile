pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('build') {
      steps {
        echo "First Pipeline Job on ${MY_NAME}"
        echo "${TEST_USER_USR}"
        echo "${TEST_USER_PSW}"
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'ABHISHEK'
    TEST_USER = credentials('test-user')
  }
}