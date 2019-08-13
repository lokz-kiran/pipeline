pipeline { 
    agent any  
    stages { 
        stage('Build') { 
            steps { 
               sh 'mvn clean'
               echo 'This is a minimal pipeline.' 
            }
        }
        stage('Compile'){
            steps{
              sh 'mvn compile'
             }
        }     
    stage('Validate'){
            steps{
              sh 'mvn validate'
             }
        }     
     stage('Pacakge'){
            steps{
              sh 'mvn package'
            }
        }     
    
   }
    
}
