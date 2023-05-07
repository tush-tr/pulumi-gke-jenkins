pipeline {
  agent any

  stages {
    stage('Deploy') {
      steps {
        sh 'ls'
        dir('react-todo-list-app'){
            sh 'docker build -t todoapp .'
        }
      }
    }
  }
}