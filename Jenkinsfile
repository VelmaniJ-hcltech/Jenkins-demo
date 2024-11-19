pipeline {
  agent any
  stages {
      stage('Build') {
          steps {
              git branch: 'main', url: 'https://github.com/VelmaniJ-hcltech/Jenkins-demo.git'
              sh 'mvn clean package'
          }
      }
  }
}
