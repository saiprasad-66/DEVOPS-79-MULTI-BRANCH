pipeline {   
    agent any

    stages {   
        stage('Master branch updated') { 
            steps { 
               sh 'echo "This is master branch updated"' 
            }
        }
     
        stage('sprint1') { 
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
