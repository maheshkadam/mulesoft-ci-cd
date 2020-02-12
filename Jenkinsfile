pipeline {
  agent any
  stages {
    stage('Deploy CloudHub') { 
      environment {
        ANYPOINT_CREDENTIALS = credentials('anypoint.credentials')
      }
      steps {
        sh 'mvn deploy -P cloudhub -Dmule.version=3.9.0 -Danypoint.username=Man94 -Danypoint.password=Man@94' 
      }
    }
  }
}