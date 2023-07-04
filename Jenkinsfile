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
            branch 'main'
        }
          steps {
               echo "Deploying Code"
          }
      }
   }
}
