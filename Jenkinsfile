pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        bat 'javac HelloWorld.java'
        bat 'java HelloWorld'
      }
    }

  }
}