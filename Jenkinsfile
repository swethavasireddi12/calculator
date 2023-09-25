pipeline {
  agent any
  environment {    
    DOCKER_IMAGE_NAME = "flask"      
    DOCKER_IMAGE_TAG = "latest"
  }
  stages {
    stage('Checkout') {           
      steps {                              
        checkout scm          
      }   
    }
    stage('Build') {

       steps {      
        script {        
          dockerImage = docker.build("${flask}:${latest}", "./")              
        }           
      }
     
        }
  }
}
  
