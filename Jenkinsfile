pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'build completed'
      }
    }

    stage('Test stages ') {
      parallel {
        stage('Test 2') {
          steps {
            echo 'running test 2'
          }
        }

        stage('test 1') {
          steps {
            echo 'running test 1'
          }
        }

      }
    }

    stage('depoly ') {
      steps {
        echo 'depolyment compelted'
      }
    }

  }
}