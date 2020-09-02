Pipeline {
  agent any 
  stages {
    stage {('Build')'{
      steps {
        echo 'Running build automation'
        sh './gradelew buid --no-doemon'
        archiveArtifacts artifacts :'dist/trainSchedule.zip'
      }  
    }
  }
}
  
