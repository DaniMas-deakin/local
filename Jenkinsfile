pipeline {
  agent any
    environment {
        DIRECTORY_PATH         = '/home/local/Jenkinsfile' 
        TESTING_ENVIRONMENT    = 'dev'
        PRODUCTION_ENVIRONMENT = 'Danielle Maslen'               
    }
    stages {
        /* stages appear below */
    }
}
  stages {
    stage('Build') {
      steps {
        echo 'Building...'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing...'
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
}
    
    
