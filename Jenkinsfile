pipeline {
  agent any
  stages {
    stage('tes') {
      parallel {
        stage('tes') {
          steps {
            echo 'test111'
          }
        }

        stage('build') {
          steps {
            echo 'build'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'build'
      }
    }

  }
}
