pipeline {
   agent any
   tools{
      maven "maven"
   }
   stage {
      stage('checkout') {
         steps {
            git branch: 'master',
            url: 'git@github.com:bingi7890/jenkins.git'
         }
      }
   }
   stage {
      stage('Build') {
         steps {
            echo "Hello-World"
         }
      }
   }
}