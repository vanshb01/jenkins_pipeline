pipeline { 
    agent any  
    stages { 
        stage('COURSES') {
          steps {
            echo 'COURSES'
          }
        }
        stage('CREDITS') { 
            steps { 
               echo 'CREDITS...' 
               sh 'python3 vansh.py'
              //bat 'mvn package'
            }
        }
   
}
    }
