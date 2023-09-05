pipeline {
  agent any
  stages {
    stage('Plan') {
      steps {
        echo 'I Have Plan to work on CICD'
      }
    }

    stage('Code') {
      steps {
        echo 'I Have Code to work on CICD'
      }
    }

    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'I Have Build to work on CICD'
          }
        }

        stage('Test') {
          steps {
            echo 'I Have Test to work on CICD'
          }
        }

        stage('Release') {
          steps {
            echo 'I Have Realse to work on CICD'
          }
        }

        stage('Deploy') {
          steps {
            echo 'I Have Deploy to work on CICD'
          }
        }

        stage('Opearte') {
          steps {
            echo 'I Have Operate to work on CICD'
          }
        }

      }
    }

  }
}