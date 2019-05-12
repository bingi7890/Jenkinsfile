
pipeline {
    agent any
    tools{
        maven "maven" 
       
     }
     stage('Checkout external proj') {
         steps {
            git branch: 'master',
            credentialsId: 'my_cred_id',
            
            url: 'git@github.com:bingi7890/jenkins.git'

           #sh "ls -lat"
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