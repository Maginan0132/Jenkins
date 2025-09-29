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
        bat 'echo "Probando..."'
      }
    }

    stage('Deploy') {
      steps {
        bat 'echo "Desplegando..."'
      }
    }

  }
}
