pipeline {
    agent any

    stages {
        stage('Git clone') {
            steps {
                echo 'Clonning the Repository'
            }
        }
            
             stage('Build') {
            steps {
                echo 'Building the code'
            }
        }
        
        stage(test){
            steps{
                echo'test the code'
            }
        }
        
        
             stage('Deploy') {
            steps {
                echo 'Deploying  the code'
            }
            
            }
            
            
            
            
    }
}
