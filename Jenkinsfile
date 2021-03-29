pipeline {
  agent any
    
  tools {nodejs "NodeJS"}
    
  stages {
        
    stage('Cloning Git') {
      steps {
        git credentialsId: 'git-creds', url: 'https://github.com/Bala-murali444/Nodejs-application-with-docker.git'
      }
    }
    
    stage('Install dependencies') {
      steps {
        sh 'npm install'
      }
    }
  }
}