pipeline {
  agent any
  stages {
    stage('getcode') {
      steps {
        bat(script: 'git clone http://github.com/kherassr/disahthelon', returnStdout: true)
      }
    }

  }
}