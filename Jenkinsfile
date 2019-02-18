pipeline {
  agent any
  tools {
    maven 'M2_HOME'
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
