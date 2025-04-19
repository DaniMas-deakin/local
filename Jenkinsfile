pipeline {
  agent any
    environment {
        DIRECTORY_PATH         = '/home/local/Jenkinsfile' 
        TESTING_ENVIRONMENT    = 'dev'
        PRODUCTION_ENVIRONMENT = 'Danielle Maslen'               
    }
   }
  stages {
    stage('Build') {
      steps {
        echo 'Compile the code and generate any necessary artefacts'
      }
    }
    stage('Build') {
      steps {
        echo 'Fetch the source code from the directory path specified by the environment variable'
      }
    }
    stage('Test') {
      steps {
        echo 'Unit tests'
        echo 'Integration tests'
      }
    }
    stage('Code Quality Check') {
      steps {
        echo 'Checking Code Quality...'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying...'
      }
    }
    stage('Approval') {
      steps {
        echo 'Approving...'
      }
    }
    stage('Deploy to Production') {
      steps {
        echo 'Deploying to Production...'
      }
    }
  }

    
    
