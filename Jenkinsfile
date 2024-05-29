pipeline {
    agent any
    stages {
        stage('print') {
            steps {
                echo "Hello world"
            }
        }
        stage ('clone') {
            steps {
                git 'https://github.com/aws-samples/eb-tomcat-snakes.git'
            }
        }
        
    }
}
