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
      stage('parallel') {
        parallel {
            stage('parallel1') {
                steps {
                    echo "We are in parallel1"
                }
            }
            stage('unitest') {
                steps {
                    echo "We are the upcoming devops engineers"
                }
            }
        }
      }
   }
}
