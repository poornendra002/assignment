pipeline {
  agent none
         stages {
           
           
           stage ('build') {
                 agent { label 'poorna' }
                 steps {
                  
                   sh '''
                    cd /home/ubuntu/jenkins/workspace/pipelineassign 
                   make ABC.exe
                   '''
                   
                 }
           }
           stage ('deploy') {
           agent { label 'poorna' }
             steps {
           echo "deploy stage"
           
         }
        }
}
}
             
      
  
        
