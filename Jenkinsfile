pipeline { 
  
   agent any

   stages {
   
     stage('Install the Dependencies') { 
        steps { 
           echo 'building application..'
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
