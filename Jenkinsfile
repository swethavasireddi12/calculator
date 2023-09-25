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
        bat 'docker run -d -p 5002:5002 --name jenkins_2 flask:v1'  
      }       
    }
  }
}
  
