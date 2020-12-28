pipeline {
agent any
tools{
maven "Maven 3.3.9"
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
