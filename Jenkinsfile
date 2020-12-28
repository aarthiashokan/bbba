pipeline {
agent any
tools{
maven "maven-hussain"
}
stages {
stage('Checkout Source') {
      steps {
        git 'https://github.com/mgsgoms/helloworld-java-maven.git'
      }
    }
stage('execute maven') {
     steps {
         sh "mvn clean install"
         }
         }
         }
         }
