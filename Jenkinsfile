pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           echo 'building a application..'
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
