pipeline {
  agent any
    environment {
        DIRECTORY_PATH         = '/home/local/Jenkinsfile' 
        TESTING_ENVIRONMENT    = 'dev'
        PRODUCTION_ENVIRONMENT = 'Danielle Maslen'   
    }
  stages {
    stage('Build') {
      steps {
        echo 'Compile the code and generate any necessary artefacts'
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
        echo 'Check the quality of the code'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploy the application to a testing environment specified by the environment variable'
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
    
    
