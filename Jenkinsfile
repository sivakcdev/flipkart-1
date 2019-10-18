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
               sh 'mvn clean package'
            }
        }
        stage ('echo') {
            steps {
               echo "build got successfull"
            }
        }                
    }
}

