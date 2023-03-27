pipeline {
  agent any
  stages {
    stage('sfsf') {
      steps {
        grypeScan(autoInstall: true, scanDest: 'registry:mohdkhalid/php-apache:latest', repName: 'myScanResult.txt')
      }
    }

  }
}