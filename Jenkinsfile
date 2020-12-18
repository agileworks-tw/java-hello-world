pipeline {
   agent any

   stages {
      stage('checkout project') {
         steps {
           checkout scm
         }
      }   
      stage('lab 101') {
         steps {
            sh label: '', script: '''java -version
            javac -version
            javac HelloWorld.java 
            java HelloWorld '''
         }
      }
   }
}