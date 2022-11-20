pipeline {
  agent none
         stages {
           
           
           stage ('build') {
                 agent { label 'poorna' }
                 steps {
                  
                   sh '''
                    cd /home/ubuntu/jenkins/workspace/assignpipeline
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
             
      
  
        
