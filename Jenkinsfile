pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Start build'
        sh 'mvn clean install'
        recordIssues()
        timestamps()
      }
    }

  }
}