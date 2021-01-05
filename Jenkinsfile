pipeline {
  agent any 
  stages {
    stage ('Clean_cache') {
      steps {
        sh 'ls' 
      }
    }
    
    stage ('Initialize') {
      steps {
        sh 'npm install' 
      }
    }
    stage ('working_directory') {
      steps {
        sh 'sudo npm start'
      }
    }
    stage ('stage3') {
      steps {
        sh 'ls'
      }
    }
    
   }  
}
