pipeline {
  tools {
    maven 'M2_HOME'
  }
  agent any
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
