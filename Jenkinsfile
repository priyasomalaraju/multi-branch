pipeline {   
    agent any

    stages {   
        stage('this is Master branch') { 
            steps { 
               sh 'echo "This is master branch"' 
            }
        }
     
        stage('this is sprint1') { 
            steps { 
               sh 'echo "sprint1 branch..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
