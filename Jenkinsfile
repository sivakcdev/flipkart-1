pipeline {
    agent { label 'master' }
    stages {
        stage ('clone') {
            steps {
               echo "please clone"
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

