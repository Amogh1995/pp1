pipeline {
  agent any
  stages {
    stage('build1') {
      steps {
        echo 'build successful'
      }
    }
    stage('') {
      steps {
        parallel(
          "test1": {
            echo 'sample test 1'
            
          },
          "test2": {
            echo 'sample test 2'
            
          }
        )
      }
    }
    stage('deploy') {
      steps {
        echo 'deply'
      }
    }
  }
}