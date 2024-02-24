Pipeline 
     {
      agent any
      stages
      {
       stage('GIT')
       {
        steps
            {
              git "https://github.com/SWAROOPADEVENDRA/7.git"
              }
       }
        stage('Run')
        {
         steps
            {
             sh "java demo.java"
            
             
            }
        }
       
      }
      }
