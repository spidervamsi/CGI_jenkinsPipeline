
node {
   checkout scm
   // do some stuff
   try {
       sh "mvn build"
   } catch (error) {
       throw error
   } finally {
       echo "hey bro"
   }
}
