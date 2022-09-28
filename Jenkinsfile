pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automation'
      sh './gradlew build --no--daemon'
        archiveSrifacts arifacts: 'dist/trainschedule.zip'
   
         }
    }
    
  }
}
