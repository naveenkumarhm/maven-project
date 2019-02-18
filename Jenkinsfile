pipeline {
  agent any
  tools {
    maven 'M2_HOME'
  }
  stages {
    stage('Build') {
      steps {
        echo 'Hello'
        sh '/usr/local/src/apache-maven/bin/mvn --v'
        sh 'sudo ssh -tt ec2-user@172.31.22.138'
        sh 'mvn --v'
        sh 'java -version'
      }
    }
  }
}
