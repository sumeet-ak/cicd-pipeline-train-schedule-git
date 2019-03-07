pipline {
  agent any
  stages {
    stage ('Build') {
      step {
        echo 'Building npm application'
      }
      step {
        sh './gradlew Build'
      }
    }
    stage ('Start application') {
      step {
        echo 'running application'
        sh 'npm start'
      }
    }
  }
}
