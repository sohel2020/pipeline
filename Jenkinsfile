pipeline {
  agent {
  docker 'test'
  }
  stages {
    stage('Build'){
      steps {
        sh 'pwd'
        sh 'hostname'
        echo 'Building...'
      }
    }
    stage('Run'){
      steps {
        echo 'Running...'
      }
    }
    stage('Finish'){
      steps {
        echo 'Finish...'
      }
    }
    stage('deploying'){
      steps {
        echo 'Deploying...'
      }
    }
  }
}
