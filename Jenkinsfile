
pipeline {
   agent any
   tools{
      maven "maven" 
   }
   stages {
      stage('Checkout external') {
         steps {
            git branch: 'master',
            credentialsId: 'c51fdbd4-4fd6-4e10-a60d-f874c3f0f3d9',
                      
            url: 'https://github.com/bingi7890/time.git'
         }
      }
      stage('Build') {
         steps {

           bat 'mvn clean package' 
            
         }
      }
   }
}