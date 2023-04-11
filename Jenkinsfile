pipeline {
   agent any
   stages {
       stage(1-'Build Code') {
           steps {
               sh "echo "Building Artifact"
           }
       }
      stage(2-'Deploy Code') {
          steps {
               sh "echo "Deploying Code"
          }
      }
      stage('3-testing code'){
        steps{
            sh 'lscpu'
        }
      }
   }
}