pipeline{
  agent any
  stages{
     stage("host name"){
       steps{
         sh '''
          hostname -i
          echo "hostname is : $(hostname -i)'
          '''
       }
     }
    stage("build"){
      steps{
        echo "this is build stage"
      }
    }
    stage("Test"){
      steps{
        echo "this is test stage"
      }
    }
    stage("deploy"){
      steps{
        echo "this is deploy step"
      }
    }
  }
}
