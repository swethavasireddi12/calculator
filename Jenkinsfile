pipeline {
  agent any
  stages {
    stage('Checkout') {           
      steps {                              
        checkout scm          
      }   
    }
    stage('Build') {
          steps {
            
            sh 'sudo docker build -t image1:v1'

          }
        }
  }
}
  
