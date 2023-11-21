pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        git(url: 'https://github.com/afsara-tasnim/simple-java-maven-app', branch: 'master', poll: true)
      }
    }

  }
}