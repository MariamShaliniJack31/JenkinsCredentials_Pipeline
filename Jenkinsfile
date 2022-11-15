pipeline {
  agent any
  environment {
    EXAMPLE_CREDENTIALS = credentials('SampleCredentials')
  }
  stages{
    stage('Example'){
      steps{
        sh('curl -u $EXAMPLE_CREDENTIALS_USR:$EXAMPLE_CREDENTIALS_PSW https://example.com')
      }
    }
  }
}
