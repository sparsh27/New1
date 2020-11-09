pipeline{
    
    agent any
    environment{
        PATH="/usr/share/maven/bin:$PATH"
    }
    stages{
        
       
        stage('Maven build') {
            
            steps{
                
                sh "mvn compile"
            }
        } 
        stage('Maven Test'){
        
            steps{
                sh "mvn test"
            }
        
        }
        
        stage('Maven package'){
            steps{
                 sh "mvn package"
            }
        }
       
	
   
            
        }
    }
