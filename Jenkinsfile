pipeline {
  agent any
 
  tools {
       maven 'maven'
  }
 
  stages {
       stage('Build') {
           steps {
               sh 'mvn -v'
               sh 'mvn clean package'
           }
       }
        stage('test') {
           steps {
               sh 'mvn test'
           }
       } 
  }
}
