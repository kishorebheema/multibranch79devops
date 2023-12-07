pipeline {   
    agent any

    stages {   
        stage('sprint1 branch new update') { 
            steps { 
               sh 'echo "This is sprint1 branch new update"' 
            }
        }
     
        stage('test') { 
            steps { 
               sh 'echo "sprint1 application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
