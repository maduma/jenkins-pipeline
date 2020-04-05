pipeline {
  agent any
  stages {
    stage('Debug') {
      steps {
          echo maduma.name
          script {
            print maduma.getClass().getName() + '@' + Integer.toHexString(maduma.hashCode())
          }
          sh 'sleep 60'
          echo maduma.name
      }
    }
  }
}
