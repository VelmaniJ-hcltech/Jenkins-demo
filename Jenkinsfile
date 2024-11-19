pipeline {
  agent any
  stages {
      stage('Build') {
          steps {
              git branch: 'main', url: 'https://github.com/VelmaniJ-hcltech/GeneralSpringBootProgExce.git'
              sh 'mvn clean package'
          }
      }
  }
}
