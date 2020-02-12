pipeline {
  agent any
  stages {
    stage('Deploy CloudHub') { 
      steps {
        bat 'mvn deploy -P cloudhub -Dmule.version=3.9.0 -Danypoint.username=Man94 -Danypoint.password=Man@94' 
      }
    }
  }
}