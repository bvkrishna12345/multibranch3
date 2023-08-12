pipeline { 
  
   agent any

   stages {
   
     stage('Install npm123 Dependencies') { 
        steps { 
           sh 'npm install' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy npm cloud application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
