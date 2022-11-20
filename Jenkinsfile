pipeline {
  agent { label 'node-java' }
         stages {
           
           
           stage ('build') {
                 agent { label 'poorna' }
                 steps {
                  
                   sh 
                   ''' cd /var/lib/jenkins/workspace
                   make
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
             
      
  
        
