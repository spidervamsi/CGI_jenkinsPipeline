node{
node {
   checkout scm
   // do some stuff
   try {
       sh "mvn clean package"
   } catch (error) {
       throw error
   } finally {
       echo "hey bro"
   }
}
}
