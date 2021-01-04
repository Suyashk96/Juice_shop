pipeline {
  agent any 
  stages {
    stage ('Initialize') {
      steps {
        sh 'npm install' 
      }
    }
    stage ('working_directory') {
      steps {
        sh 'npm start'
      }
    }
    stage ('stage3') {
      steps {
        sh 'ls'
      }
    }
    
   }  
}
