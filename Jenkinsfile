pipeline {
  agent any
  stages {
  stage('Stage 1') {
      steps {
        script {
          echo 'Stage 1'
        }
      }
    }
  stage('Stage 2') {
      steps {
        script {
          echo 'Stage 2'
        }
      }
    }
  stage('Stage 3') {
      steps {
        script {
          echo 'Stage 3'
          sh 'chmod 755 run.sh'
          sh './run.sh'
        }
      }
    }
  }
}
