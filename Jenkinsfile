pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Building the application"
            }
        }
        stage('test') {
            when {
                anyOf {
                    
                  branch 'main'           
                }
            }
            steps {
                echo "Testing the application"
                
            }
        
      }
        stage('Deploy') {
            steps {
                echo "Deploying the application"
            }
        }
    }

}    
