pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''pipeline {
    agent any

    stages {
        stage(\'Echo\') {
            steps {
                echo \'This is a test build from Blue Ocean!\'
            }
        }
    }
}
'''
          echo 'pipeline {     agent any      stages {         stage(\'Echo\') {             steps {                 echo \'This is a test build from Blue Ocean!\'             }         }     } }'
        }
      }

    }
  }