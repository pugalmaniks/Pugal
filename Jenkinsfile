pipeline {
  agent any
  stages {
    stage('Install Dependencies') {
      steps {
        echo 'building the application..'
      }
    }

    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            sh 'echo "testing application..."'
          }
        }

        stage('test1') {
          steps {
            echo 'its working fine'
          }
        }

      }
    }

    stage('Deploy application') {
      steps {
        sh 'echo "deploying application..."'
      }
    }

  }
}