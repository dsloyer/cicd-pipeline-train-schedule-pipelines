pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running buidl automation'
        sh './gredlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
 
