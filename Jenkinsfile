pipeline{
agent any
  stages{
    
      stage('Build'){
        
        steps{
          echo "you are at testing stage"
        }
        
      }
    
    post{
      always{
        
      archiveArtifacts artifacts: '' .fingerprint: true
    
    }
    }
    
    
     
  }




}
