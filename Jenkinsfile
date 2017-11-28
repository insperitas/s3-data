pipeline {
  agent any
  stages {
    stage('testing') {
      steps {
        mail(subject: 'jenkins_testing', body: 'testing has begun', from: 'james@jamestulloch.com', to: 'james@jamestulloch.com')
      }
    }
  }
}