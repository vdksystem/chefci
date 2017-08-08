pipeline {
    agent none 
    stages {
        stage('Example Build') {
            steps {
                echo 'Hello'
            }
        }
        stage('Example Test') {
            steps {
                echo 'Hello, JDK'
                sh 'java -version'
            }
        }
    }
}
