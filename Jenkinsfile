pipeline { 
    agent any  
     tools {
       maven 'LOCALMAVEN'
   }
   stages {
       stage('Build') {
           steps {
               sh "mvn clean package"
               echo "clean package completed boss"
           }
       }
   }
}

