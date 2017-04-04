pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        dockerNode(image: 'nginx') {
          sh 'echo $(hostname -f)'
        }
        
      }
    }
  }
}