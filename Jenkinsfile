pipeline { 
    agent any  
     tools {
       maven 'LOCALMAVEN'
   }
   stages {
       stage('Build') {
           steps {
               //sh "mvn build"
               try {
                   sh "mvn build"
                 // do some maven magic
                } catch (error) {
                   throw error
                } finally {
                    echo "finally boss"
                   }
               echo "clean package completed boss"
           }
       }
   }
}

