pipeline {
   agent any

   stages {
      stage('Verify Branch') {
         steps {
            echo "$GIT_BRANCH"
        }
	}

		stage('Docker build')
		{
         steps{
			   pwsh (script 'ol ')
            //powershell(echo:"ol")
            echo "$GIT_BRANCH"
         }
		}
	}  
	
}

