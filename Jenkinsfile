pipeline {
  agent any
  stages {
    stage('plan') {
      steps {
        echo 'i have a plan to work on CICD'
      }
    }

    stage('Code') {
      steps {
        echo 'i have a code to work on CICD'
      }
    }

    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'i have a build to work on CICD'
          }
        }

        stage('Test') {
          steps {
            echo 'i have a test to work on CICD'
          }
        }

        stage('Release') {
          steps {
            echo 'i have a release to work on CICD'
          }
        }

        stage('Deploy') {
          steps {
            echo 'i have a deploy to wrok on CICD'
          }
        }

        stage('Operate') {
          steps {
            echo 'i have a operate to work on CICD'
          }
        }

      }
    }

  }
}