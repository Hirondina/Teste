pipeline {
  agent any
  stages {
    stage('Inicial') {
      steps {
        sleep 1
      }
    }
    stage('Build') {
      steps {
        git(url: 'https://github.com/Hirondina/Teste.git', credentialsId: 'Hironina', branch: '1')
      }
    }
    stage('Report') {
      steps {
        powershell 'echo "Sucesso...!"'
      }
    }
  }
}