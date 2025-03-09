pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/Silent-Watcher/jenkins', branch: 'master', credentialsId: 'da9c5dac-3b6c-4263-9334-d372c7310ea8	')
      }
    }

  }
}