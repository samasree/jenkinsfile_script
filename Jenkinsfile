pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh './script.sh'
      }
    }
  }
  post {
    always {
      archive '*.jar'
    }
  }
}
