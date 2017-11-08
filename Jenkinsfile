node{
   try{
node {
   checkout scm
   // do some stuff
   try {
       sh "mvn build"
      
   } catch (error) {
       throw error
   } finally {
       echo "hey bro"
      echo "this is node 1"
   }
}
   node {
   checkout scm
   // do some stuff
   try {
       sh "mvn clean package"
   } catch (error) {
       throw error
   } finally {
       echo "hey bro"
      echo "this is node 2"
   }
}
   }
   
   finally{
       node {
   checkout scm
   // do some stuff
   try {
       sh "mvn clean package"
   } catch (error) {
       throw error
   } finally {
       echo "hey bro"
      echo "this is node 3"
   }
      
   }
}
