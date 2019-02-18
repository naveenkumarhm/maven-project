pipeline {
  agent any
  tools {
    maven 'M_HOME'
  }
  stages {
    stage('Build') {
      steps {
        echo 'Hello'
        sh 'mvn --v'
        sh 'mvn --v'
        sh 'java -version'
      }
    }
  }
}
