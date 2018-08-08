pipeline
{
   agent any
   stages{
    stage('Sample')
    {
       steps
       {
       
         bat 'mvn -version'
       }
    
    }
      stage('Clean')
      {
      
        steps
         {
         dir 'C:/Users/PRIYA/Desktop/SeleniumSpace/myFirstApp'
         bat 'mvn clean'
         }
      
      }
      
   }
   
}
