pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''cd spring
mvn spring-boot:run'''
      }
    }

    stage('test') {
      steps {
        sh '''cd spring
mvn test'''
      }
    }

  }
}