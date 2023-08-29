pipeline{
  agent any
  tools {
     maven 'maven 3'
  }
  stages{
    stage('build'){
      steps{
        bat "mvn -Dmaven.test.failure.ignore=true clean package"
      }
    }
  }
}  
