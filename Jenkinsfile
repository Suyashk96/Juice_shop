pipeline {
  agent any 
  tools {nodejs "node"}
  stages {
    stage ('Check_config') {
      steps {
        sh 'npm config ls' 
      }
    }
    
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
