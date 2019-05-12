pipeline {
   agent any
   tools{
      maven "maven"
   }
   stages {
      stage{
         git branch: 'master',
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