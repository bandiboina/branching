pipeline {   
    agent any

    stages {   
        stage('sprint2branch') { 
            steps { 
               sh 'echo "This is master branch"' 
            }
        }

        stage('test') { 
            steps { 
               sh 'echo "sprint1 application..."'
            }
        }i

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
