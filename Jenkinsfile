pipeline {
  agent any
  tools {
    maven: 'Maven 3.9.6'
  }
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
