pipeline { 
    agent any  
    stages { 
        stage('Devops') {
          steps {
            echo 'HPC'
          }
        }
        stage('courses') { 
            steps { 
               echo 'research' 
               bat 'python main.py'
               
            }
        }
   }
}
