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
            
            bat 'docker build -t image1:0.0.1.RELEASE.'

          }
     
        }
  }
}
  
