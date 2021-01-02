pipeline {
   agent any
   environment {
     GO111MODULES = 'on'
   }
   tools {
       go 'go-1.15'
   }
   stages {
     
      stage('Build') {
             steps {
                sh 'go build'
               }
       
          }
  
     }

}
