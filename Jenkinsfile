pipeline {
    agent { label 'master' }
    stages {
        stage ('clone') {
            steps {
               git clone https://github.com/sivakcdev/flipkart-1.git
            }
        }
        stage ('Build') {
            steps {
               mvn clean package
            }
        }
        stage ('echo') {
            steps {
               echo "build got successfull"
            }
        }                
    }
}

