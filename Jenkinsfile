pipeline{
    tools{
maven 'maven-3.8.1'
}
    agent{
        label 'master'
    }
    stages{
      stage('git stage'){
          steps{
            git 'https://github.com/tnareshece/hellospringboot-cicdWithHelm.git'  
              
          }
          
      } 
      stage('build stage'){
          steps{
            sh 'mvn clean package'  
              
          }
          
      } 
      
        
    }
}
