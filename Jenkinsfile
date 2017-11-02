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
        git(url: 'git@github.com:Hirondina/teste1.git', credentialsId: 'Hironina', branch: '1')
      }
    }
    stage('Report') {
      steps {
        powershell 'echo "Sucesso...!"'
      }
    }
  }
}