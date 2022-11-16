pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
       echo 'Building'...
         bat mvn clean
      }
    }
    stage('Test') {
      steps {
        echo 'Tested'...
        bat mvn test
      }
      stage('Deploy') {
      steps {
        echo 'Deployed'..
          bat mvn compile
      }
    }
  }
}
