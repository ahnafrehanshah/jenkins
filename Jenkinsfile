pipeline { 
    agent any  
    stages { 
        stage('sample1') {
          steps {
            echo 'Starting'
          }
        }
        stage('sample 2') { 
            steps { 
               echo 'printing req. data..' 
               bat 'python solution.py'
            }
        }
   
}
    }
