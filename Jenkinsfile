pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Build1'
          }
        }

        stage('Parallel Build') {
          steps {
            echo 'parallel'
          }
        }

      }
    }

    stage('git') {
      steps {
        echo 'git'
      }
    }

  }
}