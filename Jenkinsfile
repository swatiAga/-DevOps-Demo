pipeline {
  agent any
  stages {
    stage('sfsf') {
      steps {
        grypeScan(autoInstall: true, scanDest: 'docker:mohdkhalid/php-apache:latest', repName: 'myScanResult.txt')
      }
    }

  }
}