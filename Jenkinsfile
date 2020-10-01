pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''cd spring
mvn spring-boot:run -Dserver.port=8083
'''
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