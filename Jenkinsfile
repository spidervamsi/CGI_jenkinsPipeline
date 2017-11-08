pipeline { 
    agent any  
     tools {
       maven 'LOCALMAVEN'
   }
   stages {
       stage('Build') {
           steps {
               sh "mvn build"
               echo "scm completed boss"
           }
       }
   }
}
