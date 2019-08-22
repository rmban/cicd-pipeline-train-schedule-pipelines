pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running Build Automation Third time!!'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
        }  
       }
      }
     }
