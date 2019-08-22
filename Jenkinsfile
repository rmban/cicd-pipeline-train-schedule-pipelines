pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running Build Automation Second time!!'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
        }  
       }
      }
     }
