pipeline {
  agent {
    node {
      label 'docker'
    }

  }
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'testing'
          }
        }

        stage('parrallel') {
          steps {
            echo 'parrallel'
          }
        }

      }
    }

    stage('build') {
      steps {
        echo 'build'
      }
    }

    stage('clean up') {
      steps {
        echo 'clean up '
      }
    }

  }
}