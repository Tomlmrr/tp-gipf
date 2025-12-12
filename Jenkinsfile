pipeline {
  agent any
  environment {
    HTTP_PROXY  = 'http://proxy1-rech.uphf.fr:3128'
    http_proxy  = 'http://proxy1-rech.uphf.fr:3128'
    HTTPS_PROXY = 'http://proxy1-rech.uphf.fr:3128'
    https_proxy = 'http://proxy1-rech.uphf.fr:3128'
    NO_PROXY    = 'localhost,127.0.0.1'
  }
  stages {
    stage('Build') {
      steps {
        sh './gradlew build'
      }
    }
  }
}
