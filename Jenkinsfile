pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/Maginan0132/Jenkins', branch: 'main')
        sh 'mvn clean install'
      }
    }
    stage('Test') {
      steps {
        sh 'mvn test' [cite: 99]
      }
    }
    stage('Deploy') {
      steps {
        sh 'echo "Desplegando..."' [cite: 104]
      }
    }
  }
}
