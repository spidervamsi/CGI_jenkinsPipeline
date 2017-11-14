pipeline {
	agent any
	stages {
   	stage('test'){
			steps {
			    echo 'hey im test'
				echo '${BUILD_NO}
			sh 'mvn clean package'
			}
		}

              }
   	post {
   	  	always {
		 
                  echo 'hey I am here'
			}
		}

}
