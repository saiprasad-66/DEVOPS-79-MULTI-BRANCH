pipeline {   
    agent any

    stages {   
        stage('hotfix branch updating') { 
            steps { 
               sh 'echo "This is hotfix branch updating"' 
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
