pipeline {
  agent any
  stages {
    stage('tes1111') {
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
