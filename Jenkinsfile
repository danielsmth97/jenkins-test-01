pipeline {
  agent {
    docker {
      image 'containerd:1.2.2'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'echo "hello world"'
      }
    }
  }
}