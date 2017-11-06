pipeline { 
    agent any  
     tools {
       maven 'LOCALMAVEN'
   }
   stages {
       stage('Build') {
           steps {
                checkout scm 
               echo "scm completed boss"
           }
       }
   }
}
