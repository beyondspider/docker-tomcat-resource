pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'docker build -t beyondspider/tomcat-resource:latest .'
      }
    }
  }
}