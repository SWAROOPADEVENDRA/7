pipeline 
     {
      agent any
      stages
      {
       stage('git')
       {
        steps
            {
              git ""
              }
       }
        stage('run')
        {
         steps
            {
             sh "java demo.java"
             sh "python3 main.py"
             }
        }
       
      }
      }
