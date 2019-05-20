
pipeline {
   agent any
   tools{
      maven "maven" 
   }
   stages {
      stage('Checkout external') {
         steps {
            git branch: 'master',
            
                      
            url: 'https://github.com/bingi7890/time-track.git'
         }
      }
      stage('Build') {
         steps {

           echo "Hello" 
            
         }
      }
   }
}
