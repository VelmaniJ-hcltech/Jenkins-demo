pipeline {
  agent any
  stages {
      stage('Build') {
          steps {
              git branch: 'development', url: 'https://github.com/VelmaniJ-hcltech/GeneralSpringBootProgExce.git'
              sh 'mvn clean package'
          }
      }
  }
}
