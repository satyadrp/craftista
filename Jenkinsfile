pipeline {
  agent any
  stages {
    stage('build') {
      agent any
      steps {
        dir(path: 'voting') {
          sh 'mvm compile'
        }

      }
    }

  }
}