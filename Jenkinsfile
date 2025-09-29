pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git url: 'https://github.com/Maginan0132/Jenkins.git', branch: 'main'
      }
    }

    stage('Test') {
      steps {
        sh 'echo "Probando..."'
      }
    }

    stage('Deploy') {
      steps {
        sh 'echo "Desplegando..."'
      }
    }

  }
}
