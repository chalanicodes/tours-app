pipeline {
    agent any
    tools {
      nodejs '16.17.0'    
    }
    stages {
        stage('Build') { 
          steps {
            sh 'npm install' 
          }
        }
    }
}