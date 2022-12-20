pipeline {
  agent any

 environment {
  ABC="abc"
  devops= credentials("devops")
 }

  stages {
   stage('New') {
   environment {
   XYZ="xyz"
   }
     steps {
       echo 'Hello World'
       echo "${XYZ}"
       echo "${devops}"
     }
    }
   }

   post{
    always {
     echo 'OK'
    }
  }
}
