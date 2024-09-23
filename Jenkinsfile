pipeline {
  agent any
  stages {
    stage('checkout') {
      agent any
      environment {
        GIT_USERNAME = 'tahir'
        GIT_EMAIL = 'tahir@mail.com'
      }
      steps {
        git 'https://github.com/TahirIshaq/practice'
      }
    }

  }
}