Pipeline {
  agent any 
  stages {
    stage {('Build')'{
      steps {
        echo 'Running build automation'
        sh './gradlew build --no-doemon'
        archiveArtifacts artifacts :'dist/trainSchedule.zip'
      }  
    }
  }
}
  
