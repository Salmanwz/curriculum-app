pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/Salmanwz/curriculum-app', branch: 'dev')
      }
    }

    stage('Script') {
      steps {
        sh 'ls -la'
      }
    }

  }
}