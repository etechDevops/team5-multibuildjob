pipeline {
   agent any
   stages {
       stage('Build Code') {
           steps {
              echo "Building Artifact"
              echo "testing"
           }
       }
      stage('Deploy Code') {
        when {
            branch 'uat'
        }
          steps {
               echo "Deploying Code"
          }
      }
   }
}
