pipeline {
  agent 'any'
  stages {
    stage ("Build project") {
      steps {
        sh './gradlew build'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
