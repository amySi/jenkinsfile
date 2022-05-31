pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'building'
          }
        }

        stage('parallel build') {
          steps {
            echo 'parallel build'
          }
        }

      }
    }

    stage('testing') {
      steps {
        echo 'testing'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploy'
      }
    }

  }
}