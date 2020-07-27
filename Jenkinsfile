pipeline {
  agent any
  stages {
    stage ('Build Hello World') {
      steps {      withMaven(maven : 'maven_3.5.4') {
          sh 'mvn package'
        }
       }
    }
  }
}
