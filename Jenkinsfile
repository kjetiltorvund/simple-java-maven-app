pipeline {
  agent any
  stages {
    stage('Start Message') {
      steps {
        echo 'Starting build'
      }
    }
    stage('Building Task') {
      steps {
        build 'mvn clean install'
      }
    }
    stage('Finished Message') {
      steps {
        echo 'Finished'
      }
    }
  }
}