pipeline {
   agent any
   tools{
      maven "maven"
   }
   stages {
      stage('checkout') {
         steps {
            git 'https://github.com/bingi7890/jenkins.git'
         }
      }
      stage('Build') {
         steps {
            echo "Hello-World"
         }
      }
   }
}