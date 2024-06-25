pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/xalxnder/jenkins-101', branch: 'main')
      }
    }

    stage('List ') {
      steps {
        sh 'ls -la'
      }
    }

  }
}