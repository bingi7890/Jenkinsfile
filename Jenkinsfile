pipeline {
   agent any
   tools{
      maven "maven"
   }
   stages {
      stage('checkout') {
         steps {
            git branch: "master"
               url: "https://github.com/bingi7890/jenkins.git"
            
         }
      }
      stage('Build') {
         steps {
            echo "Hello-World"
         }
      }
   }
}