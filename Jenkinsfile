pipeline {
  agent any
  stages {
    stage('build assets') {
      steps {
        sh 'install'
        sh '''npm run scss:prod
'''
        sh '''npm run script:prod
'''
      }
    }

  }
}