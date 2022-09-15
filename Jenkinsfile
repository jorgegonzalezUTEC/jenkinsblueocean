pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Building...'
          }
        }

        stage('Build Paralelo') {
          steps {
            echo 'Parallel Building...'
          }
        }

      }
    }

    stage('Test') {
      steps {
        echo 'Testing...'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying...'
      }
    }

  }
}