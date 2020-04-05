pipeline {
  agent any
  stages {
    stage('Debug') {
      steps {
          echo maduma.name
          script {
            print maduma.hashCode()
          }
          sh 'sleep 60'
          echo maduma.name
      }
    }
  }
}
