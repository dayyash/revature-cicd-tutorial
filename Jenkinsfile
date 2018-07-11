pipeline {
  agent any
  stages {
    stage('Nonsense') {
      steps {
        echo 'Hello!'
      }
    }
    stage('Maven Build') {
      steps {
        sh 'mvn clean package -DskipTests'
      }
    }
  }
}