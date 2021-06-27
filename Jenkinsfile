pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
               sh 'mvn install'
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
