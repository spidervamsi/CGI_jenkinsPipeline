pipeline {
	agent any
	stages {
   	stage('test'){
			steps {
			    echo 'hey im test' 
			sh 'mvn clean package'
			}
		}

              }
   	post {
   	  	always {
		 echo "Running $ENV.BUILD_ID on $ENV.JENKINS_URL" 
                  echo 'hey I am here'
			}
		}

}
