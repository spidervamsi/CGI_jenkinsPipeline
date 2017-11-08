pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                sh 'mvn clean package'
                echo 'Hello World'
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
