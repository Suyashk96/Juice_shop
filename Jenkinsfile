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
        sh 'sudo npm install' 
      }
    }
    stage ('working_directory') {
      steps {
        sh 'sudo npm start --unsafe-perm'
      }
    }
    stage ('stage3') {
      steps {
        sh 'ls'
      }
    }
    
   }  
}
