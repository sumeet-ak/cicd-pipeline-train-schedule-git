pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Building npm application'
        sh './gradlew Build'
      }
          }
    stage ('Start application') {
      steps {
        echo 'running application'
        sh 'npm start'
      }
    }
  }
}
