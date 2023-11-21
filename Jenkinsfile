pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/afsara-tasnim/simple-java-maven-app', branch: 'master', poll: true)
      }
    }

    stage('Shell Script') {
      steps {
        sh 'ls -la'
      }
    }

  }
}