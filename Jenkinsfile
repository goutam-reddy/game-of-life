pipeline {
  agent any 
stages {
  stage('Clean'){
  steps{
    sh 'mvn clean'
     }
  }
  stage('validate'){
    steps{
      sh 'mvn validate'
           }
        }
  stage('compile'){
    steps{
      sh 'mvn compile'
          }
     }
 stage('test'){
    steps{
      sh 'mvn test'
         }
     }
stage('verify'){
  steps{
    sh 'mvn verify'
          }
      }    
   stage('install'){
       steps{
    sh 'mvn install'
           }
      }  
     }
   }
