pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'sucesso!'
          }
        }
        stage('') {
          steps {
            echo 'Sucesso!'
          }
        }
      }
    }
    stage('Teste') {
      steps {
        error 'Erro...!'
      }
    }
  }
}