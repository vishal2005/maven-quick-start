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
                expression {
                 env.BRANCH_NAME == 'dev'   
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
