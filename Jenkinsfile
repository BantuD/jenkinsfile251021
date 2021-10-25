pipeline{
    agent any
    stages{
      stage('Build'){
          steps{
          echo 'Build Stage'
              bat 'mvn clean'
          }
      }
      stage('Test skipped'){
          steps{
          bat 'echo skipped'
          }         
      }
        stage('Stage 3'){
          steps{
         echo 'Stage 3'
          }         
      }
        stage('Stage 4'){
          steps{
         echo 'Stage4'
          }         
      }
        stage('Stage 5'){
          steps{
         echo 'Stage5'
          }         
      }
    }
}