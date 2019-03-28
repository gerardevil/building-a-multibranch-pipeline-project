pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "Hello world!"'
      }
    }
    stage('Docker Build') {
      steps {
        sh 'sudo docker build -t test-image .'
      }
    }
  }
}
