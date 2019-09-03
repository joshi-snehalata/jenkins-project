pipeline {
  agent any
  stages {
    stage('TestNode') {
      steps {
        rqtfReport(nameReport: 'TestReport', modelReport: 'Analysis Result', templateReport: 'default.html', lang: 'English')
      }
    }
  }
}