pipeline {
  agent none
  stages {
    stage('First Step') {
      agent {
        docker {
          image 'maven:latest'
          args '--network = host'
        }

      }
      steps {
        sh 'echo "Hello"'
      }
    }

  }
}