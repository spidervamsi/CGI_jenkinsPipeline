pipeline {
	agent any
	stages {
   	stage('test'){
			steps {
				sh 'mvn test' 
			}
		}

   	stage('compile'){
			steps {
				sh 'mvn compile' 
			}
		}

   	stage('build'){
			steps {
				sh 'mvn build' 
			}
		}

   	stage('run'){
			steps {
				sh 'mvn spring-boot:run' 
			}
		}

}
   	post {
   	  	always {
                  echo 'hey I am here'
			}
		}

}
