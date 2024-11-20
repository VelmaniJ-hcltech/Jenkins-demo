pipeline {
  agent any
  tools {
    maven "Default-Maven"
  }
  stages {
      stage('Build') {
          steps {
              git branch: 'development', url: 'https://github.com/aamirpatel/GeneralSpringBootProgExce.git'
              sh 'mvn clean package'
          }
      }
  }
}
