pipeline {
   agent any
   stages {
       stage('1-Build Code') {
           steps {
              echo "Building Artifact"
              echo "testing"
           }
       }
      stage('2-Deploy Code') {
          steps {
               echo "Deploying Code"
          }
      }
      stage('3-testing codes'){
        steps{
            sh 'lscpu'
        }
      }
   }
}
