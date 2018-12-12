pipeline {
  agent any
    stages {
       stage('CodeCheckout') {
         steps {
            script {
               checkout scm
                 def mvnHome = tool 'maven-1'
            }
         }
       }
    }
}
                
                 
    
      
