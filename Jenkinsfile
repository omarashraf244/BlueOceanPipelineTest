pipeline {
  agent any
  stages {
    stage('Test1') {
      parallel {
        stage('Test1') {
          steps {
            echo 'Good Morning'
          }
        }

        stage('Deploy') {
          steps {
            input(message: 'Are you sure you want to deploy ', ok: 'yes')
          }
        }

      }
    }

  }
}