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
         
         bat 'mvn clean'
         }
      
      }
      
   }
   
}
