pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Build Step'
                sleep 10
            }
        }
        stage('Test') {
            steps {
                echo 'Test step'
            }
        }
      stage('deploy') {
          steps {
              echo 'Deploy step'
              sleep 10
          }
      }
      stage('docker') {
        steps {
            echo 'Image step'
        }
      }
    }
  }
    
