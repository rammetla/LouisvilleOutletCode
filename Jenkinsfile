pipeline
{
   agent any
   stages{
    stage('Version Check')
    {
       steps
       {
       
         bat 'mvn -version'
       }
    
    }
      stage('Build')
      {
      
        steps
         {
            dir ('C:/Users/PRIYA/Desktop/SeleniumSpace/myFirstApp')
            {
                bat 'mvn clean install'
               
            }
         
         }
      
      }
     
      
      stage ('Deploy')
      {
      
         steps
         {
         
         build job: 'Continuous Deployment -  Build Deployment'

         
         }
      
      }
      
      stage ('Test')
      {
      
         steps
         {
            dir ('C:/Users/PRIYA/Desktop/SeleniumSpace/MyWebAppTest')
            {
             bat 'RunSeleniumTest'
            }
         
         
         }
      
      }
      
   }
   
}
