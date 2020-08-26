pipeline {
    agent any
    stages {
        stage('CI') {
            steps { 
                snDevOpsStep()
                echo 'CI' 
            }         
        }
        stage('UAT') {
            steps { 
                snDevOpsStep()
                echo 'UAT' 
            }         
        }
        stage('PROD') {
            steps { 
                snDevOpsStep()
                echo 'PROD' 
            }         
        }
    }
}
