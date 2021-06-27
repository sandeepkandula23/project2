pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
               sh "mvn package"
                 echo 'Welcome to build'
                // 
            }
        }
        stage('Test') { 
            steps {
                echo 'Welcome to Test1'
                // 
            }
        }
        stage('Deploy') { 
            steps {
                echo 'Welcome to Deploy'
                // 
                
            }
        }
    }
}
