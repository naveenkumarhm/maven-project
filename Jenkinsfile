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
        sh 'sudo ssh -tt ec2-user@172.31.22.138'
        sh 'mvn --v'
        sh 'java -version'
      }
    }
  }
}
