pipeline {
  agent any
  stages {
    stage('Build Assets') {
      steps {
        echo 'Build Started'
        isUnix()
		mvn clean install
      }
    }

  }
}