pipeline{
   agent any
  stages{
    stage('compile stage') {
      steps {
         def mvnHome = tool name: 'M2_HOME', type: 'maven'
         sh "${mvnHome}/bin/mvn  clean compile"
        }
      }
     }
    
    /*stage('testing stage') {
      steps {
        withMaven(maven : 'M2_HOME'){
          
         sh 'mvn test'
        }
      }
          }
    
    stage('Deployment stage') {
      steps {
        withMaven(maven : 'M2_HOME'){
          
         sh 'mvn deploy'
        }
      }
          }
    
  }

}*/
