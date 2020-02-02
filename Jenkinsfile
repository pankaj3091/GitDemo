pipeline{
  agent any
  stages{
      stage('Compile stage'){
        steps{
          sh 'mvn clean compile'
          }
          
        }
    stage('Testing Stage'){
    steps{
               sh 'mvn clean compile'
      }
        }    
    stage('Deployment Stage'){
      steps{
           sh 'mvn deploy'
          }
      }
    }
}
