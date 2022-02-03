pipeline {
  
  agent any
  
  stages {
    
    stage("build") {
      
      steps {
        echo 'building the application...executing nodejs build'
        nodejs('node-16.3.0') {
          sh 'npm install'
        }
        
      }
      
    }
    
    stage("test") {
      
      steps {
        echo 'testing the application...'
        
      }
      
    }
    
    stage("deploy") {
      
      steps {
        echo 'deploying the application...'
        
      }
      
    }
    
  }
  
}
