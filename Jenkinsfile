pipeline {
  agent {
     node { label 'workstation' }
    }

   stages {

      stage('code Checkout') {
        steps {
          echo 'code checkout'
           }
      }

     stage('BUILD') {
        steps {
           sh 'mvn package'
            }
      }

    stage('UNIT TESTS') {
        steps {
           echo 'UNIT TEST'
           //sh 'mvn test'
            }
        }

    stage('CODE ANALYSIS') {
        steps {
          echo 'CODE ANALYSIS'
           }
        }

    stage('SECURITY SCAN') {
       steps {
          echo 'SECURITY SCAN'
          }
       }
    stage('PUBLISH A ARTIFACT WITH VERSION') {
       steps {
          echo 'PUBLISH A ARTIFACT WITH VERSION'
          }
      }

   }

}


