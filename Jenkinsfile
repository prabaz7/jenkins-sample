pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'building stage'
      }
    }

    stage('Test') {
      steps {
        echo 'Test stage'
      }
    }

    stage('Approval') {
      steps {
        input(message: 'du u want to proceed deployment?', id: '1')
      }
    }

    stage('Deploy') {
      steps {
        echo 'This is Deploy stage'
      }
    }

  }
}