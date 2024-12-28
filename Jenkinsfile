pipeline {
  agent any
  stages {
    stage "Build" {
       echo 'Running Build Automation'
       sh './gradlew build'
       archiveArtifacts artifacts: 'dist/trainSchedule.zip'
    }
  }
}
