pipeline {
  agent any
  stages {
    stage('Stage 1') {
      steps {
        sh '''echo "Stage 1"
echo "npm start"
'''
        echo '"Stage 2 using Print Message function"'
      }
    }

    stage('Stage 2') {
      steps {
        echo '"stage 2 "'
      }
    }

  }
}