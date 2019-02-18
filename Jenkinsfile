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
        sh 'git --version'
        sh 'mvn install'
         }
        }
        stage('Test'){
          steps {
           sh 'mvn test'
           sh 'ls'
        }
        }
      
   
  }
}
