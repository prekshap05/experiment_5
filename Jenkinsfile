pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git branch: 'main', url: 'https://github.com/your-username/HelloWorld.git'
      }
    }
    stage('Build') {
      steps {
        bat 'javac HelloWorld.java'
      }
    }
    stage('Run') {
      steps {
        bat 'java HelloWorld'
      }
    }
  }
}
