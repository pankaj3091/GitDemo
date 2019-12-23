pipeline{
  agent any
  stages{
      stage('----Clean----'){
        steps{
           bat 'mvn clean compile'
          }
        }
    stage('----Test----'){
    steps{
          bat 'mvn clean compile'
          }
        }    
    stage('----Package----'){
      steps{
           bat 'mvn deploy'
          }
      }
    }
