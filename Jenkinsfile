pipeline{
 agent any
  stages{
    stage('Code Checkout'){
     steps{
          echo '***************************************************************'
          echo '********************performing git checkout********************'
          echo '***************************************************************'
          }
         }
     stage('MSBuild'){
       steps{
         sh './build.sh'
         }
        }
      }
    }
      
