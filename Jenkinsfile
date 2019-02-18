pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Hello'
        sh '/usr/local/src/apache-maven/bin/mvn --v'
        sh 'ssh ec2-user@172.31.22.138'
        sh 'mvn --v'
        sh 'java -version'
      }
    }
  }
}
