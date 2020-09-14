pipeline {
  agent any
  stages {
    stage('Build Assets') {
      steps {
        echo 'Build Started'
        sh 'mvn clean install'
      }
    }

  }
}