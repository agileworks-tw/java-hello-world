pipeline {
   agent any

   stages {
      stage('lab 101') {
         steps {
            git 'https://github.com/agileworks-tw/java-hello-world.git'
            sh label: '', script: '''java -version
            javac -version
            javac HelloWorld.java 
            java HelloWorld '''
         }
      }
   }
}