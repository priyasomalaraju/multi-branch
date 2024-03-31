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
               sh 'echo "sprint1 application..."'
            }
        }

        stage("sprint2 branch") { 
             steps { 
                sh 'echo "this is sprint2 branch......"'
            }
        }  
    }
}
