pipeline {
    agent any

stages {  
  
    stage ('Build') {
     steps {
    echo " running build automation"
     sh './gradlew build --no-daemon'
    archievArtifacts artifacts: 'dist/trainSchedule.zip'
}
   
}
}
}
