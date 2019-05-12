
pipeline {
   agent any
   tools{
      maven "maven" 
       
   }
     
   stage('Checkout external') {
      steps {
         git branch: 'master',
         credentialsId: 'my_cred_id',
         url: 'git@github.com:bingi7890/jenkins.git'
      }
          
   }
   stages {
      stage('Build') {
         steps {
              
            echo "Hello-World"
         }
      }
   }
}