pipeline {
  agent any

  stages {
    stage('Deploy') {
      steps {
        sh 'ls'
        sh 'sudo apt install docker.io'
        dir('react-todo-list-app'){
            sh 'docker build -t todoapp .'
        }
      }
    }
  }
}