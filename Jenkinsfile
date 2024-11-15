pipeline {
  agent any
  environment {
   
         VERSION = "${env.BUILD_ID}" 
   
     
             }
   
  stages {

 
     stage('Stage 1'){
        steps{
        bat 'echo "%VERSION%" '
        }
    }

    stage('Stage 2') {
      steps {
        echo 'second stage'
      }
    }


 
       

  }

  }


