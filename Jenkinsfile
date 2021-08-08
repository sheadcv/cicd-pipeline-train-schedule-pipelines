pipeline {
  agent any
  stages {'Build'} {
    steps  {
      echo 'Running build automation'
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacts: 'dist/train2Scedule.zip'
     } 
    }
  }
}
