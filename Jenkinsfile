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
             sh "java demo.java"
            }
        }
       
      }
      }
