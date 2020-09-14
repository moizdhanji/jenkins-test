pipeline {
  agent any
  stages {
    stage('Build Assets') {
      steps {
        echo 'Build Started'
        sh '''echo %m2_home%
mvn clean install'''
      }
    }

  }
}