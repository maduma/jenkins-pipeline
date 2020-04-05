pipeline {
  agent any
  stages {
    stage('Debug') {
      steps {
          echo maduma.name
          script {
            print maduma.getClass().getName()
          }
          sh 'sleep 60'
          echo maduma.name
      }
    }
  }
}
