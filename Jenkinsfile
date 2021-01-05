pipeline {
  agent any 
  stages {
    stage ('Clean_cache') {
      steps {
        sh 'npm cache clean --force' 
      }
    }
    
    stage ('Initialize') {
      steps {
        sh 'npm install' 
      }
    }
    stage ('working_directory') {
      steps {
        sh 'npm start --unsafe-perm'
      }
    }
    stage ('stage3') {
      steps {
        sh 'ls'
      }
    }
    
   }  
}
