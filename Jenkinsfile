pipeline { 
    agent any  
    stages { 
        stage('Devops') {
          steps {
            echo 'credits - 4'
          }
        }
        stage('SPM') {
          steps {
            echo 'credits-5'
          }
        }
        stage('Communication') { 
            steps { 
               echo 'credits-6' 
               bat 'python vansh.py'
              //bat 'mvn package'
            }
        }
   
}
    }
