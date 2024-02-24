pipeline 
     {
      agent any
      stages
      {
       stage('git')
       {
        steps
            {
              git "https://github.com/SWAROOPADEVENDRA/7.git"
              }
       }
        stage('run')
        {
         steps
            {
            sh "main.py"
            sh "java demo.java"
            }
        }
       
      }
      }
