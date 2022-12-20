pipeline {
  agent any

 enivornment {
  ABC="abc"
 }

  stages {
   stage('New') {
   environment {
   XYZ="xyz"
   }
     steps {
       echo 'Hello World'
       echo "${XYZ}"
     }
    }
   }

   post{
    always {
     echo 'OK'
    }
  }
}
