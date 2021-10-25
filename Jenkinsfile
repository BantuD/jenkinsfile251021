pipeline{
    agent any
    stages{
      stage('Build'){
          steps{
          echo 'Build Stage'
              bat 'echo mvn clean goal is running........'
          }
      }
      stage('Test'){
          steps{
          bat 'echo skipped the testing stage'
          }         
      }
        stage('Stage 3'){
          steps{
         echo 'Stage 3'
          }         
      }
        stage('Stage: integration '){
          steps{
         echo 'Stage4'
          }         
      }
        stage('Stage: Deployment'){
          steps{
         echo 'Stage5'
          }         
      }
    }
}