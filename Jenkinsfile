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
            
            bat 'sudo docker build -t image1:v1'

          }
        }
  }
}
  
