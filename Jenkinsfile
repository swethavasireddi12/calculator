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
        bat 'docker build -t flask:v1 .'          
      }
     
        }
    stage('Run Image') {     
      steps {            
        bat 'docker run -d --name container1 flask:v1'          
      }       
    }
  }
}
  
