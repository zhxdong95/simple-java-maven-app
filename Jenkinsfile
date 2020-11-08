pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'mvn clean package'
      }
    }

    stage('Test') {
      steps {
        echo 'Test stage ...'
        sh 'mvn test'
      }
    }

  }
}