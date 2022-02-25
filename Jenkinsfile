pipeline {
  agent {
    docker {
      image 'jenkins/agent:latest'
    }
  }
  stages {
    stage('build and start'){
      steps{
        sh './install.sh'
      }
    }
  }
}