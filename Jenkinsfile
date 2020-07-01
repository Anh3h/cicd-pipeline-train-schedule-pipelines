pipeline {
  agent 'any'
  stages {
    stage ("Build project") {
      steps {
        sh './gradlew build'
        achiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
