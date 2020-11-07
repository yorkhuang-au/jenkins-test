pipeline {
  agent {
    docker {
      image 'python'
    }

  }
  stages {
    stage('Test') {
      agent {
        docker {
          image 'python'
        }

      }
      steps {
        sh 'echo "Hello world"'
        echo 'no way'
      }
    }

  }
}