

pipeline{
  agent any
    steps {
      stage ('Build') {
        steps {
             echo " running build automation "
               sh './gradlew build --no-deamon'
               archiveArtifacts artifacts: 'dist/trainSchdule.zip'
               }
           }
      }
      
   }
        
