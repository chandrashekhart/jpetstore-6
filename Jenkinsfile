pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'my first jenkins pipeline'
        sh './mvnw clean compile'
      }
    }

    stage('Unit Test') {
      steps {
        sh './mvnw test'
      }
    }

  }
}